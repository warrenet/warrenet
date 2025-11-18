---
applyTo: ".github/workflows/**/*.yml"
---

# GitHub Actions Workflow Instructions

This repository uses several GitHub Actions workflows to automatically update the README profile page.

## Existing Workflows

1. **Update GitHub Activity** (`update-activity.yml`)
   - Updates recent GitHub activity every 6 hours
   - Uses `jamesgeorge007/github-activity-readme@master`

2. **Update WakaTime Stats** (`update-wakatime.yml`)
   - Updates coding statistics daily
   - Requires `WAKATIME_API_KEY` secret

3. **Update Tech Joke** (`tech-joke.yml`)
   - Updates programming joke daily at 8 AM UTC
   - Uses JokeAPI v2 for content

## Workflow Standards

### Structure
- Always include both `schedule` and `workflow_dispatch` triggers
- Use descriptive job and step names
- Pin action versions for stability (avoid `@master` in production)
- Include comments explaining complex steps

### Scheduling
- Use appropriate cron schedules to avoid rate limiting
- Consider GitHub Actions usage limits
- Stagger workflows to distribute load
- Test schedules thoroughly

### Security
- Never hardcode secrets or tokens
- Use `${{ secrets.SECRET_NAME }}` for sensitive data
- Limit workflow permissions to minimum required
- Regularly rotate API keys

### Error Handling
- Include error handling where appropriate
- Add notifications for workflow failures
- Use `continue-on-error` judiciously
- Log meaningful error messages

### Dependencies
- Keep action versions up to date
- Pin to specific versions (e.g., `@v3` instead of `@master`)
- Review action security and maintenance status
- Document any third-party actions used

### Testing
- Test workflows with `workflow_dispatch` before scheduling
- Verify all secrets are properly configured
- Check that README markers are correctly placed
- Validate API integrations work as expected

## Maintenance

- Review workflows quarterly for deprecated actions
- Monitor GitHub Actions usage and costs
- Update API endpoints when services change
- Archive or remove unused workflows

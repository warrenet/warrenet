---
applyTo: "**/*"
---

# General Coding Instructions

This is a GitHub profile repository that showcases skills, projects, and activities through an interactive README.

## Project Overview

This repository serves as a personal profile page on GitHub, featuring:
- Live statistics and badges
- Automated daily updates via GitHub Actions
- Integration with third-party services (WakaTime, GitHub Stats APIs)
- Dynamic content sections

## Code Style and Quality

- Keep all code clean, maintainable, and well-documented
- Follow existing patterns and conventions in the repository
- Ensure all URLs and external integrations are working correctly
- Validate markdown syntax for all documentation files

## GitHub Actions Workflows

- All workflows should be efficient and avoid unnecessary API calls
- Use appropriate cron schedules to avoid rate limiting
- Include `workflow_dispatch` for manual triggering
- Always validate workflow syntax before committing

## Documentation Standards

- Maintain consistent formatting in README.md
- Preserve all existing sections and their structure
- Keep badges and shields up to date
- Ensure all links are valid and accessible

## Testing and Validation

- Verify that GitHub Actions workflows run successfully
- Test all external integrations and API calls
- Validate markdown rendering on GitHub
- Check that all badges and images display correctly

## Security Considerations

- Never commit secrets or API keys directly
- Use GitHub Secrets for sensitive data
- Keep dependencies up to date
- Follow GitHub's security best practices

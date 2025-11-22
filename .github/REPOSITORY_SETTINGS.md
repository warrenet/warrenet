# Repository Settings Recommendations

This document provides recommended settings for optimal repository management.

## General Settings

### Repository Name
- Name: `warrenet`
- Description: "My GitHub profile README - showcasing my skills, projects, and activities"
- Topics: `profile`, `readme`, `github-profile`, `portfolio`, `github-actions`, `automation`
- Website: Add your personal website or portfolio URL

### Features
- ✅ Issues
- ✅ Discussions (recommended for community engagement)
- ✅ Wiki (optional, for documentation)
- ✅ Projects (optional, for project management)

### Security
- ✅ Enable Dependabot alerts
- ✅ Enable Dependabot security updates
- ✅ Enable Code scanning alerts (if applicable)
- ✅ Enable Secret scanning
- ✅ Enable Private vulnerability reporting

## Branch Protection Rules (for `main` branch)

### Protect matching branches
- ✅ Require a pull request before merging
  - ✅ Require approvals: 1 (if working with others)
  - ✅ Dismiss stale pull request approvals when new commits are pushed
  - ✅ Require review from Code Owners
  
- ✅ Require status checks to pass before merging
  - ✅ Require branches to be up to date before merging
  - Required checks: CI, markdown-lint, link-check
  
- ✅ Require conversation resolution before merging
- ✅ Require linear history (optional, keeps history clean)
- ✅ Include administrators (enforce rules for everyone)

### Merge Options
- ✅ Allow squash merging (recommended for cleaner history)
- ⬜ Allow merge commits (optional)
- ⬜ Allow rebase merging (optional)
- ✅ Automatically delete head branches

## Actions Settings

### General
- ✅ Allow all actions and reusable workflows
- ✅ Allow actions created by GitHub
- ✅ Allow actions by Marketplace verified creators

### Workflow Permissions
- ⬜ Read repository contents permission (more restrictive)
- Or ✅ Read and write permissions (needed for automated updates)
- ✅ Allow GitHub Actions to create and approve pull requests

## Secrets Configuration

The following secrets should be configured in Settings > Secrets and variables > Actions:

1. `WAKATIME_API_KEY` - For WakaTime statistics integration
   - Get from: https://wakatime.com/settings/account
   - Keep this secret secure

## Environment Protection

If using environments for deployments:
- Set up environment protection rules
- Require reviewers for production deployments
- Add deployment branch restrictions

## Webhooks and Services

Optional integrations to consider:
- Discord/Slack notifications for repository activity
- Codecov or similar for code coverage tracking
- Integration with project management tools

## Repository Visibility

- ✅ Public (required for GitHub profile README to display)

## Social Preview

Upload a custom image for social media sharing:
- Recommended size: 1280x640 pixels
- Should showcase your profile or branding

## Pages (Optional)

If you want to host additional documentation:
- Enable GitHub Pages
- Source: Deploy from a branch or GitHub Actions
- Custom domain: Optional

---

**Note**: These are recommendations. Adjust based on your specific needs and workflow preferences.

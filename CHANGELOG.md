# Changelog

All notable changes to this repository will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- Comprehensive GitHub Actions workflow upgrades
- Community health files (CODE_OF_CONDUCT.md, CONTRIBUTING.md, SECURITY.md)
- Enhanced issue templates with feature request and config
- Markdown linting and link checking automation
- Stale issue/PR management workflow
- First-time contributor greeting workflow
- Auto-labeling for issues and pull requests
- Enhanced README with animated typing banner
- Improved GitHub stats sections with multiple visualizations
- Additional technology badges (databases, tools)
- LICENSE file (MIT)
- FUNDING.yml for GitHub Sponsors
- Comprehensive .gitignore file
- Repository settings recommendations document
- Labeler configuration for automatic PR labeling

### Changed
- Updated all GitHub Actions to latest versions (v3 → v4)
- Pinned all workflow actions to specific versions (removed @master)
- Fixed deprecated `::set-output` syntax to use `$GITHUB_OUTPUT`
- Enhanced CI workflow with better validation and reporting
- Improved CODEOWNERS file with detailed ownership rules
- Expanded Dependabot configuration to cover more ecosystems:
  - Docker
  - Go modules
  - Python pip
  - Terraform
  - npm (with improved configuration)
- Updated tech-joke workflow to use direct API calls instead of third-party actions
- Improved workflow permissions following principle of least privilege

### Fixed
- Workflow syntax and validation issues
- Deprecated GitHub Actions syntax
- Missing permissions declarations in workflows

## [1.0.0] - Initial Profile Setup

### Added
- Initial README profile with live statistics
- GitHub Activity auto-update workflow
- WakaTime integration workflow
- Tech joke daily update workflow
- Basic CI workflow
- Bug report issue template
- Profile views and follower badges
- Skills and technologies showcase
- GitHub trophies and streak stats
- Social media links

---

## How to Use This Changelog

- **Added** for new features.
- **Changed** for changes in existing functionality.
- **Deprecated** for soon-to-be removed features.
- **Removed** for now removed features.
- **Fixed** for any bug fixes.
- **Security** in case of vulnerabilities.

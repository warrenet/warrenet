---
applyTo: "README.md"
excludeAgent: "code-review"
---

# README Documentation Instructions

This file contains specific instructions for working with the README.md profile documentation.

## Structure Requirements

The README.md serves as the main profile page and must maintain its structure:
1. Header section with profile views and follower badges
2. About Me section
3. Skills & Technologies with proficiency indicators
4. Current Projects section
5. Activity and stats sections with live data
6. Social media links
7. Inspirational quote footer

## Editing Guidelines

### Content Updates
- Preserve all HTML comments that mark dynamic sections (e.g., `<!--START_SECTION:waka-->`)
- Do not modify content between automated update markers
- Keep all badge URLs valid and properly formatted
- Maintain consistent badge styling (use `for-the-badge` style)

### Formatting Standards
- Use proper markdown headings hierarchy
- Keep sections separated with `---` dividers
- Ensure all images have alt text
- Maintain alignment and visual consistency

### Badge and Link Management
- Use shields.io for consistent badge styling
- Verify all external service integrations are working
- Keep profile statistics services up to date
- Test all social media and contact links

### Dynamic Content Sections
Never manually edit these sections (they're auto-updated by workflows):
- `<!--START_SECTION:waka-->` to `<!--END_SECTION:waka-->`
- `<!--START_SECTION:activity-->` to `<!--END_SECTION:activity-->`
- `<!-- JOKE-OF-THE-DAY:START -->` to `<!-- JOKE-OF-THE-DAY:END -->`

## Best Practices

- Preview all changes locally or in a markdown editor
- Verify that new sections maintain visual consistency
- Keep the README mobile-friendly
- Ensure fast loading times by optimizing image URLs
- Maintain professional tone and content quality

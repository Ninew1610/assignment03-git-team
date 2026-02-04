# The Triangle Devs - AI Coding Instructions

## Project Overview
This is a static HTML website for "The Triangle Devs," a developer team based in Thailand. The project consists of three linked HTML pages serving as a team portfolio site with minimal dependencies.

## Architecture & File Structure

### Pages
- **`index.html`** - Landing page with team introduction and story
- **`about.html`** - Team member bios with student IDs and personal information
- **`portfolio.html`** - Individual project showcases from team members

### Key Pattern: Shared Navigation
All pages share a consistent navigation bar with links to Home, Portfolio, and About Us. The navigation styling is duplicated across files using inline `<style>` tags.

## Styling Conventions

### Inline Styles
All CSS is embedded in `<style>` tags within each HTML document. Common patterns:
- **Layout**: `max-width: 800px; margin: 0 auto; padding: 20px;` for centered content container
- **Navigation**: Dark gray background (`#333`) with white text for nav links
- **Cards**: Box-based layout for content sections (bio-box, project-card) with borders/background colors

### Content Sections
- `.member-list` - Gray background (`#f4f4f4`) with rounded borders
- `.bio-box` - Light blue background (`#eef`) with left border accent
- `.project-card` - Simple border-based layout

## Microsoft Office Metadata
All files contain embedded Microsoft Office XML metadata (`mso:` namespace) from editing in SharePoint/Office Online. When updating HTML, preserve the XML comment block between `</head>` tags to maintain document properties.

## Placeholder Content Pattern
- Student names/IDs use `[XXXXXXXX]` format
- Thai language sections use `[เขียนแนะนำตัวเองสั้นๆ ตรงนี้...]` comments
- These are intentional placeholders for team members to fill in

## Navigation Links
Links use hardcoded relative paths: `../../../Shared%20Documents/General/Week03/homework_git_team/[page].html`
- These reflect the original SharePoint directory structure
- When modifying navigation, update all three files consistently

## Common Tasks

### Adding Team Member Bio
Edit `about.html` - duplicate the `<article class="bio-box">` section and update name, student ID, and bio content.

### Adding Portfolio Project
Edit `portfolio.html` - duplicate the `.project-card` div and update project details and descriptions.

### Styling Updates
Update the shared `<style>` sections in all three files to maintain visual consistency.

## Notes for AI Agents
- No external CSS files or JavaScript dependencies
- Simple vanilla HTML structure - suitable for static hosting
- Links between pages use relative paths; test navigation after any path changes
- Document was created in SharePoint (evident from embedded metadata) - preserve Office metadata when editing

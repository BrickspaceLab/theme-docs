# Accordion

## Overview

A collapsible accordion container that provides an expandable/collapsible content area with a header button. Uses Alpine.js for toggle functionality and includes smooth animations when enabled.

## Common use cases

- Create FAQ sections with expandable questions and answers
- Organize product details or specifications in collapsible sections
- Group related content that can be expanded on demand
- Enable pre-opened option to show content by default

## Child blocks

This block includes the following nested blocks:

- Container (for accordion label)
- Container (for accordion content)

## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Enable internal padding | Adds internal padding to the accordion content | Checkbox (default: true) |
| Enable horizontal padding | Adds horizontal padding around the accordion | Checkbox (default: false) |
| Enable top padding | Adds top padding around the accordion | Checkbox (default: false) |
| Enable bottom padding | Adds bottom padding around the accordion | Checkbox (default: false) |
| Color scheme | Controls the background and text colors | Body (default), Neutral, Accent 1, Accent 2, Accent 3, Shade 1, Shade 2, Shade 3, Primary, Secondary, Tertiary, Blur, Transparent |
| Color border | Controls the border color | Body (default), Subtle (default), Strong, Primary, Secondary, Tertiary, None. Visible when border position is not blank |
| Border position | Controls where borders appear | None (default), Top, Bottom, Left, Right, Top and bottom, Left and right, All |
| Enable pre opened | Opens the accordion by default | Checkbox (default: false) |
| Enable single open | Allows only one accordion item to be open at a time | Checkbox (default: false) |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |


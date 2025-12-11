# Menu page

## Overview

A dynamic menu container component that creates a multi-level navigation menu with hover and click interactions. Supports up to three levels of navigation (parent, child, and grandchild links) with customizable styling and optional thumbnail images for menu items.

## Common use cases

- Use consistent image sizes for navigation thumbnails (recommended 64px)
- Consider mobile usability when configuring menu depth and content
- Keep menu labels concise for better layout
- Test hover/click interactions across different devices
- Ensure navigation images follow the correct naming convention
- Consider using dropdown icons for better UX when submenus are present

## Child blocks

This block includes the following nested blocks:

- Menu item

## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Menu | Select the menu to display | Link list picker (default: main-menu) |
| Parent font family | Font family for parent menu links | Body (default), Heading, Subheading, Accent. Visible when parent font size contains type-- |
| Parent font size | Font size for parent menu links | Smaller, Small, Default (default), Big, Bigger, Heading 1, Heading 2, Heading 3, Heading 4, Heading 5, Heading 6 |
| Enable dropdown icons | Shows chevron icons for menu items with dropdowns | Checkbox (default: true) |
| Child font family | Font family for child menu links | Body (default), Heading, Subheading, Accent. Visible when child font size contains type-- |
| Child font size | Font size for child menu links | Smaller, Small, Default (default), Big, Bigger, Heading 1, Heading 2, Heading 3, Heading 4, Heading 5, Heading 6 |
| Grandchild font family | Font family for grandchild menu links | Body (default), Heading, Subheading, Accent. Visible when grandchild font size contains type-- |
| Grandchild font size | Font size for grandchild menu links | Smaller, Small, Default (default), Big, Bigger, Heading 1, Heading 2, Heading 3, Heading 4, Heading 5, Heading 6 |
| Page color scheme | Background and text color scheme for menu page overlay | Body (default), Neutral, Accent 1, Accent 2, Accent 3, Shade 1, Shade 2, Shade 3, Primary, Secondary, Tertiary, Blur, Transparent |
| Page color border | Border color for menu page items | Subtle (default), Strong |
| Enable internal padding | Adds internal padding to menu page content | Checkbox (default: true) |
| Gap size | Spacing between menu items | None, Default (default), XS, SM, MD, LG, XL |
| Enable padding | Adds padding around the menu container | Checkbox (default: false) |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |


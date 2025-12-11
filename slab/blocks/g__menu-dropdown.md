# Menu dropdown

## Overview

A container component that handles menu dropdown functionality and styling. Provides a flexible menu system with support for nested links, dropdowns, and featured content blocks.

## Common use cases

- Use for main navigation menus that require dropdowns
- Configure menu_columns setting for full-width mega menus
- Add navigation images to enhance visual hierarchy
- Customize fonts and spacing to match site design
- Leverage blocks to add featured content in dropdowns

## Child blocks

This block includes the following nested blocks:

- Menu item

## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Menu | Select the menu to display | Link list picker (default: main-menu) |
| Parent font family | Font family for parent menu links | Standard (default), Heading, Subheading, Accent. Visible when parent font size contains type-- |
| Parent font size | Font size for parent menu links | Smaller, Small, Default (default), Big, Bigger, Heading 1, Heading 2, Heading 3, Heading 4, Heading 5, Heading 6 |
| Enable dropdown icons | Shows chevron icons for menu items with dropdowns | Checkbox (default: true) |
| Enable link as button | Converts parent links with children to buttons | Checkbox (default: false) |
| Child font family | Font family for child menu links | Standard (default), Heading, Subheading, Accent. Visible when child font size contains type-- |
| Child font size | Font size for child menu links | Smaller, Small, Default (default), Big, Bigger, Heading 1, Heading 2, Heading 3, Heading 4, Heading 5, Heading 6 |
| Grandchild font family | Font family for grandchild menu links | Standard (default), Heading, Subheading, Accent. Visible when grandchild font size contains type-- |
| Grandchild font size | Font size for grandchild menu links | Smaller, Small, Default (default), Big, Bigger, Heading 1, Heading 2, Heading 3, Heading 4, Heading 5, Heading 6 |
| Menu columns | Comma-separated list of menu items to display as full-width columns | Text input |
| Dropdown layout | Layout style for dropdown menus | Stacked (default), Inline |
| Dropdown gap size | Spacing between dropdown menu items | None, Default (default), XS, SM, MD, LG, XL |
| Dropdown enable internal padding | Adds internal padding to dropdown content | Checkbox (default: true). Visible when dropdown is not full-width |
| Dropdown enable margin | Applies margin based on theme settings | Checkbox (default: false). Visible when dropdown is full-width |
| Dropdown color scheme | Background and text color scheme for dropdown | Body (default), Neutral, Accent 1, Accent 2, Accent 3, Shade 1, Shade 2, Shade 3, Primary, Secondary, Tertiary, Blur, Transparent |
| Dropdown color border | Border color for dropdown | Body (default), Subtle (default), Strong, Primary, Secondary, Tertiary, None |
| Dropdown color divider | Divider color between stacked dropdown items | Subtle (default), Strong |
| Top spacing | Padding space at the top of parent links | 0 - 300 px (default: 0) |
| Bottom spacing | Padding space at the bottom of parent links | 0 - 300 px (default: 0) |
| Gap size | Spacing between menu items | None, Default (default), XS, SM, MD, LG, XL |
| Enable horizontal padding | Adds horizontal padding around the menu | Checkbox (default: false) |
| Horizontal alignment | Controls horizontal alignment of the menu | Left (default), Center, Right |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |


# Badges


## Overview

A customizable product badges block that displays various types of informational badges for products. The block can show sold out status, savings information, low stock alerts, custom product tags, and metafield-based badges. Badges can be displayed as plain text or styled badge elements with extensive customization options for positioning, colors, and layout.


## Common use cases

- Use overlay positioning for product images to create eye-catching promotional badges
- Set appropriate stock thresholds based on your inventory management needs
- Use consistent color schemes across badge blocks for visual cohesion
- Consider using text display for minimal designs and badge display for more prominent styling
- Configure metafield badges for custom product attributes like "Featured", "New", or "Limited Edition"
- Test badge visibility on both light and dark backgrounds when using overlay positioning


## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Product | Select the product to display badges for | Product picker |
| Show sold out badge | Displays a "Sold out" badge when the product is unavailable | Checkbox (default: false) |
| Savings badge | Controls how savings are displayed when product is on sale | None, Percent (default), Amount |
| Stock threshold | Minimum stock quantity before showing low stock badge (0 = never show) | Number input |
| Metafield badges | Comma-separated metafield references for custom badges (namespace.key format) | Text input |
| Enable horizontal padding | Adds horizontal padding around the badges | Checkbox (default: false) |
| Enable top padding | Adds top padding around the badges | Checkbox (default: false) |
| Enable bottom padding | Adds bottom padding around the badges | Checkbox (default: false) |
| Color scheme | Controls the background and text color combination for badges | Body, Neutral, Accent 1, Accent 2, Accent 3, Shade 1, Shade 2, Shade 3, Primary, Secondary, Tertiary, Blur, Transparent. Visible when display type is "badge" |
| Border color | Controls the border color | Body, Subtle (default), Strong, Primary, Secondary, Tertiary, None. Visible when display type is "badge" |
| Text color | Controls the text color | Default (default), Alternative, Primary, Secondary, Tertiary, Neutral, Shade |
| Enable color difference | Applies mix-blend-difference for better visibility on varied backgrounds | Checkbox (default: false) |
| Display type | Controls how badges are displayed | Text, Badge (default) |
| Font family | Controls the font family used for badges | Standard, Heading, Subheading, Accent |
| Font size | Controls the font size of badges | Smaller, Small, Default (default), Big, Bigger, Heading 1, Heading 2, Heading 3, Heading 4, Heading 5, Heading 6 |
| Horizontal alignment | Controls horizontal alignment | Left (default), Center, Right |
| Vertical alignment | Controls vertical alignment when overlay is enabled | Top (default), Bottom. Visible when enable overlay is true |
| Enable overlay | Positions badges as an overlay on product images | Checkbox (default: false) |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |


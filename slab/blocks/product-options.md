# Options


## Overview

A comprehensive product variant selection block that provides flexible display options for product options including colors, sizes, and other variants. The block supports both button-based and dropdown-based selection interfaces, with advanced features like swatches, tooltips, and unavailability indicators. It integrates with Alpine.js for interactive behavior and handles complex variant logic including availability checking and option state management.


## Common use cases

- Use button selection for better user experience when you have few variant options
- Enable swatches for color options to provide visual selection feedback
- Consider using unavailable indication to guide customers toward available variants
- Use grid layout when displaying many options to maintain organized appearance
- Configure appropriate gap sizes based on your design system and available space
- Enable tooltips for swatch-only displays to show option names on hover
- Test responsive behavior to ensure smooth transitions between desktop dropdowns and mobile drawers
- Ensure proper styling of disabled states when using unavailability indicators


## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Product | Select the product to display options for | Product picker |
| Variant selection | Controls how non-swatch variants are displayed | Buttons (default), Dropdowns |
| Unavailable indication | Controls how unavailable variants are indicated | None, Empty (default), Selected |
| Show labels | Displays labels for each option | Checkbox (default: true) |
| Swatch selection | Controls how swatch options (colors) are displayed | Buttons (default), Dropdowns |
| Show swatch | Displays color swatches for color options | Checkbox (default: true) |
| Show tooltip | Displays tooltips showing option names on swatch hover | Checkbox (default: true). Visible when swatch selection is "buttons" |
| Show labels | Displays text labels with swatches | Checkbox (default: false) |
| Layout | Controls the layout of swatch and label | Stacked, Inline (default). Visible when show labels is true |
| Size | Size of the swatch indicators | 8 - 120 px (default: 16). Visible when show swatch is true |
| Radius | Border radius for swatches | None, Default, Sm, Md, Lg, Xl, 2xl, Full (default). Visible when show swatch is true |
| Enable horizontal padding | Adds horizontal padding around the options | Checkbox (default: false) |
| Enable top padding | Adds top padding around the options | Checkbox (default: false) |
| Enable bottom padding | Adds bottom padding around the options | Checkbox (default: false) |
| Gap size | Spacing between option elements | None, Default (default), Xs, Sm, Md, Lg, Xl |
| Text color | Controls the text color | Default (default), Alternative, Primary background, Primary foreground, Secondary background, Secondary foreground, Tertiary background, Tertiary foreground, Neutral background, Neutral foreground, Shade |
| Button color | Color scheme for option buttons | Primary, Secondary, Tertiary, Neutral, Plain (default), Outline, Inverted outline, Blur, Link, Inverted link |
| Button color selected | Color scheme for selected option buttons | Primary, Secondary, Tertiary, Neutral, Plain, Outline (default) |
| Font family | Controls the font family used for option labels | Standard, Heading, Subheading, Accent. Visible when show labels is true |
| Font size | Controls the font size of option labels | Smaller, Small, Default, Big, Bigger, Heading 1, Heading 2, Heading 3, Heading 4, Heading 5, Heading 6. Visible when show labels is true |
| Button size | Controls the size of option buttons | Extra small, Small (default), Standard, Large |
| Horizontal alignment | Controls horizontal alignment | Left (default), Center, Right |
| Enable grid layout | Uses a grid layout instead of flex wrap | Checkbox (default: false) |
| Row desktop | Number of columns in grid on desktop | 1 - 12 (default: 4). Visible when enable grid layout is true |
| Row mobile | Number of columns in grid on mobile | 1 - 3 (default: 2). Visible when enable grid layout is true |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |


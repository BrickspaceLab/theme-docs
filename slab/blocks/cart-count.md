# Cart count


## Overview

Displays a cart count indicator that shows the current number of items in the cart. Can be displayed inline or as a floating badge with configurable position. The count is dynamically updated using Alpine.js.


## Common use cases

- For floating layout, adjust x/y positions to align properly with your cart icon
- Consider visibility settings for responsive designs when using multiple cart icons
- Display cart item count in headers or navigation areas
- Use as a badge overlay on cart icons


## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Digit limit | Maximum number of digits to display before showing "+" suffix (e.g., 2 = "99+") | Number input (default: 2) |
| Button color | Color scheme for the cart count indicator | Primary (default), Secondary, Tertiary, Neutral, Plain, Outline, Inverted outline, Blur, Link, Inverted link |
| Font family | Controls the font family used for the count | Standard, Heading, Subheading, Accent. Visible when font size contains 'type--' |
| Font size | Controls the font size of the count | Smaller, Small, Default (default), Big, Bigger, Heading 1, Heading 2, Heading 3, Heading 4, Heading 5, Heading 6 |
| Radius | Border radius for the count indicator | None, Default (default), Sm, Md, Lg, Xl, 2xl, Full |
| Layout | Controls the layout of the count indicator | Float, Inline (default) |
| Horizontal position | Horizontal position as percentage (for float layout) | 0 - 100 % (default: 55). Visible when layout is "float" |
| Vertical position | Vertical position as percentage (for float layout) | 0 - 100 % (default: 0). Visible when layout is "float" |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |


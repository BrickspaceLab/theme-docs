# Float

## Overview

A float block that wraps other theme or app blocks and positions them absolutely according to x and y coordinate settings.

## Common use cases

- Position blocks at specific coordinates on the page for floating elements like tooltips, badges, or overlays
- Ensure the parent container has position: relative for proper positioning
- Use responsive positioning for different desktop and mobile layouts
- Apply rotation effects for dynamic floating content

## Child blocks

This block includes the following nested blocks:

- All theme blocks
- App blocks

## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Color scheme | Controls the background and text colors | Body, Neutral, Accent 1, Accent 2, Accent 3, Shade 1, Shade 2, Shade 3, Primary, Secondary, Tertiary, Blur, Transparent (default) |
| Color border | Controls the border color | Body (default), Subtle (default), Strong, Primary, Secondary, Tertiary, None. Visible when border position is not blank |
| Enable color difference | Applies mix-blend-difference for visual contrast | Checkbox (default: false) |
| Border position | Controls where borders appear | None (default), Top, Bottom, Left, Right, Top and bottom, Left and right, All |
| Vertical alignment (desktop) | Vertical position percentage on desktop | 0 - 100 % (default: 50) |
| Horizontal alignment (desktop) | Horizontal position percentage on desktop | 0 - 100 % (default: 50) |
| Width (desktop) | Width of the floating block as viewport percentage | 5 - 100 % (default: 30) |
| Rotation (desktop) | Rotation angle in degrees | 0 - 360 deg (default: 15) |
| Vertical alignment (mobile) | Vertical position percentage on mobile | 0 - 100 % (default: 50) |
| Horizontal alignment (mobile) | Horizontal position percentage on mobile | 0 - 100 % (default: 50) |
| Width (mobile) | Width of the floating block as viewport percentage | 5 - 100 % (default: 70) |
| Rotation (mobile) | Rotation angle in degrees | 0 - 360 deg (default: 15) |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |
| Scroll animation | Adds scroll-triggered animations | None (default), Fade, Slide up, Slide down, Slide left, Slide right, Zoom |


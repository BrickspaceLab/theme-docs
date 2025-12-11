# Default grid

## Overview

A flexible grid container component that allows for dynamic layout configuration of child blocks. Supports both app and theme blocks in a responsive grid layout with customizable columns for desktop and mobile views.

## Common use cases

- Display multiple blocks in a grid layout for product grids, image galleries, or any content that benefits from a grid structure
- Configure desktop and mobile columns based on content size and screen real estate
- Use gap settings to control spacing between grid items
- Enable scroll animations for dynamic content reveals

## Child blocks

This block includes the following nested blocks:

- Grid products
- Grid articles
- Grid collections
- Grid gallery
- Grid recommendations
- Grid recent
- Grid item
- All theme blocks
- App blocks

## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Top spacing | Padding space at the top of the container | 0 - 300 px (default: 0) |
| Bottom spacing | Padding space at the bottom of the container | 0 - 300 px (default: 0) |
| Enable horizontal padding | Adds horizontal padding around the container | Checkbox (default: false) |
| Gap size | Controls spacing between grid items | None, Default (default), XS, SM, MD, LG, XL |
| Color scheme | Controls the background and text colors | Body, Neutral, Accent 1, Accent 2, Accent 3, Shade 1, Shade 2, Shade 3, Primary, Secondary, Tertiary, Blur, Transparent (default) |
| Color border | Controls the border color | Body (default), Subtle (default), Strong, Primary, Secondary, Tertiary, None. Visible when border position is not blank |
| Border position | Controls where borders appear | None (default), Top, Bottom, Left, Right, Top and bottom, Left and right, All |
| Row desktop | Number of columns in grid on desktop | 1 - 8 (default: 5) |
| Row mobile | Number of columns in grid on mobile | 1 - 3 (default: 2) |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |
| Scroll animation | Adds scroll-triggered animations | None (default), Fade, Slide up, Slide down, Slide left, Slide right, Zoom |


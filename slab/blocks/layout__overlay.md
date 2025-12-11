# Fixed

## Overview

A flexible overlay container component that allows positioning child blocks in fixed positions on the screen corners. Supports both app and theme blocks with customizable corner positioning and z-index control.

## Common use cases

- Use for floating/fixed position blocks on the screen like chat widgets, promotional banners, or notification elements
- Configure position and spacing using the block settings
- Control visibility for different device sizes

## Child blocks

This block includes the following nested blocks:

- All theme blocks
- App blocks

## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Enable padding | Adds padding around the overlay content | Checkbox (default: true) |
| Gap size | Controls spacing between child blocks | None, Default (default), XS, SM, MD, LG, XL |
| Color scheme | Controls the background and text colors | Body, Neutral, Accent 1, Accent 2, Accent 3, Shade 1, Shade 2, Shade 3, Primary, Secondary, Tertiary, Blur, Transparent (default: Accent 1) |
| Color border | Controls the border color | Body (default), Subtle (default), Strong, Primary, Secondary, Tertiary, None. Visible when border position is not blank |
| Border position | Controls where borders appear | None (default), Top, Bottom, Left, Right, Top and bottom, Left and right, All |
| Rotation | Rotates the overlay content | None (default), Right 90°, Left 90° |
| Horizontal position | Controls horizontal positioning of the overlay | Left (default), Center, Right |
| Vertical position | Controls vertical position as percentage from top | 0 - 100 % (default: 100) |
| Enable margin | Applies margin based on theme settings | Checkbox (default: false) |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |


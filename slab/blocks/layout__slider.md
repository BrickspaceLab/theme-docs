# Slider

## Overview

A flexible slider/carousel container component that provides smooth scrolling functionality for child content blocks. Features auto-scroll capabilities, navigation arrows, progress indicators, and responsive behavior.

## Common use cases

- Create image galleries, product carousels, or testimonial sliders
- Enable auto-scroll for rotating content displays
- Use navigation arrows and indicators for better user control
- Configure gap sizes to control spacing between slider items
- Show controls on hover for a cleaner interface

## Child blocks

This block includes the following nested blocks:

- Slider item
- Slider products
- Slider articles
- Slider collections
- Slider gallery
- Slider recommendations
- Slider recent

## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Show arrows | Displays navigation arrows for the slider | Checkbox (default: true) |
| Show indicators | Displays progress indicators (dots or numbers) | Checkbox (default: true) |
| Show controls on hover | Only shows controls when hovering over the slider | Checkbox (default: false). Visible when show arrows or show indicators is true |
| Show scrollbar | Displays the scrollbar for manual scrolling | Checkbox (default: false) |
| Show progress bar | Displays a progress bar at the top when auto-scroll is enabled | Checkbox (default: false). Visible when enable auto scroll is true |
| Enable instant transition | Removes smooth scrolling for instant transitions | Checkbox (default: false) |
| Enable auto scroll | Automatically scrolls through slides | Checkbox (default: false) |
| Auto scroll delay | Time delay between auto-scroll transitions | 0 - 20 s (default: 0). Visible when enable auto scroll is true |
| Top spacing | Padding space at the top of the slider | 0 - 300 px (default: 0) |
| Bottom spacing | Padding space at the bottom of the slider | 0 - 300 px (default: 0) |
| Enable horizontal padding | Adds horizontal padding around the slider | Checkbox (default: false) |
| Gap size | Controls spacing between slider items | None, Default (default), XS, SM, MD, LG, XL |
| Color scheme | Controls the background and text colors | Body, Neutral, Accent 1, Accent 2, Accent 3, Shade 1, Shade 2, Shade 3, Primary, Secondary, Tertiary, Blur, Transparent (default) |
| Color border | Controls the border color | Body (default), Subtle (default), Strong, Primary, Secondary, Tertiary, None. Visible when border position is not blank |
| Border position | Controls where borders appear | None (default), Top, Bottom, Left, Right, Top and bottom, Left and right, All |
| Arrow color | Controls the color scheme for navigation arrows | Primary (default), Secondary, Tertiary, Neutral, Plain, Outline, Inverted outline, Blur, Link, Inverted link |
| Button size | Controls the size of navigation arrows | Extra small (default), Small, Standard, Large |
| Indicator color | Controls the color scheme for progress indicators | Primary (default), Secondary, Tertiary, Neutral, Plain, Outline, Inverted outline, Blur |
| Indicator radius | Controls the border radius of indicator dots | None, Default, SM, MD, LG, XL, 2XL, Full (default) |
| Control alignment | Controls alignment of navigation controls | Left (default), Center, Right |
| Control placement | Controls vertical position of navigation controls | Top, Middle, Bottom, Below (default) |
| Enable scroll margin | Applies margin based on theme settings for scroll padding | Checkbox (default: false) |
| Vertical alignment | Controls vertical alignment of slider content | Top (default), Middle, Bottom |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |
| Scroll animation | Adds scroll-triggered animations | None (default), Fade, Slide up, Slide down, Slide left, Slide right, Zoom |


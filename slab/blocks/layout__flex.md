# Flex grid

## Overview

A flexible container component that provides customizable flex layout options for child blocks. Enables responsive alignment, spacing, and visibility controls through the theme editor.

## Common use cases

- Create flexible row or column layouts for content organization
- Use horizontal direction for side-by-side content arrangements
- Use vertical direction for stacked content layouts
- Configure gap sizes to control spacing between flex items
- Adjust alignment settings to position content within the flex container

## Child blocks

This block includes the following nested blocks:

- Flex item

## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Top spacing | Padding space at the top of the container | 0 - 300 px (default: 0) |
| Bottom spacing | Padding space at the bottom of the container | 0 - 300 px (default: 0) |
| Enable horizontal padding | Adds horizontal padding around the container | Checkbox (default: false) |
| Gap size | Controls spacing between flex items | None, Default (default), XS, SM, MD, LG, XL |
| Color scheme | Controls the background and text colors | Body, Neutral, Accent 1, Accent 2, Accent 3, Shade 1, Shade 2, Shade 3, Primary, Secondary, Tertiary, Blur, Transparent (default) |
| Color border | Controls the border color | Body (default), Subtle (default), Strong, Primary, Secondary, Tertiary, None. Visible when border position is not blank |
| Border position | Controls where borders appear | None (default), Top, Bottom, Left, Right, Top and bottom, Left and right, All |
| Direction | Controls the flex direction | Horizontal (default), Vertical |
| Horizontal alignment (row) | Controls horizontal alignment when direction is horizontal | Left (default), Center, Right, Between. Visible when direction is horizontal |
| Vertical alignment (row) | Controls vertical alignment when direction is horizontal | Start (default), Middle, End, Between, Stretch. Visible when direction is horizontal |
| Vertical alignment (column) | Controls vertical alignment when direction is vertical | Start (default), Middle, End, Between. Visible when direction is vertical |
| Horizontal alignment (column) | Controls horizontal alignment when direction is vertical | Left (default), Center, Right, Between, Stretch (default). Visible when direction is vertical |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |
| Scroll animation | Adds scroll-triggered animations | None (default), Fade, Slide up, Slide down, Slide left, Slide right, Zoom |


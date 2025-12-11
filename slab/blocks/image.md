# Image


## Overview

A flexible image block component that renders a single image with customizable styling options. Supports responsive display, color schemes, aspect ratios, and alignment controls.


## Common use cases

- Consider image optimization by setting appropriate max_width
- Choose aspect ratio based on image content and layout needs
- Utilize color schemes to maintain fallback colors or backgrounds when using transparent images


## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Image | The image to display | Image picker |
| Enable horizontal padding | Adds horizontal padding around the content | Checkbox (default: false) |
| Enable top padding | Adds top padding around the content | Checkbox (default: false) |
| Enable bottom padding | Adds bottom padding around the content | Checkbox (default: false) |
| Color scheme | Controls the background color scheme | Body (default), Neutral, Accent 1, Accent 2, Accent 3, Shade 1, Shade 2, Shade 3, Primary, Secondary, Tertiary, Blur |
| Border color | Controls the border color | Body, Subtle (default), Strong, Primary, Secondary, Tertiary, None. Visible when border position is not empty |
| Border position | Controls which sides have borders | None (default), Top, Bottom, Left, Right, Top and bottom, Left and right, All |
| Radius | Controls the border radius | None (default), Default, Sm, Md, Lg, Xl, 2xl, Full |
| Enable aspect ratio | Forces the image to maintain a specific aspect ratio | Checkbox (default: false) |
| Aspect ratio | The aspect ratio to maintain | Square, Landscape, Portrait, None. Visible when enable aspect ratio is true |
| Width | Controls the width of the image | 5 - 100 % (default: 100) |
| Horizontal alignment | Controls horizontal alignment | Left (default), Center, Right |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |
| Scroll animation | Adds scroll-based animations to the block | None (default), Fade, Slide up, Slide down, Slide left, Slide right, Zoom |


# Container


## Overview

A flexible container block that holds other theme or app blocks with configurable spacing, gap size, and display visibility options.


## Common use cases

- Use this container to group related blocks with consistent spacing
- Adjust visibility settings to create different layouts for mobile and desktop
- Create structured layouts with nested content
- Apply shared settings to multiple child blocks


## Child blocks

This block includes the following nested blocks:

- All theme blocks
- App blocks


## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| URL | Optional URL to make the entire container clickable | URL input |
| Enable background image or video | Enables background image or video settings | Checkbox (default: false) |
| Image background desktop | Desktop background image | Image picker. Visible when enable background image or video is true |
| Image background mobile | Mobile background image | Image picker. Visible when enable background image or video is true |
| Video background | Background video | Video picker. Visible when enable background image or video is true |
| Show video on mobile | Displays video on mobile devices | Checkbox (default: true). Visible when enable background image or video is true |
| Show entire image | Shows the full image without cropping | Checkbox (default: false). Visible when enable background image or video is true |
| Top spacing | Spacing above the container | 0 - 300 px (default: 0) |
| Bottom spacing | Spacing below the container | 0 - 300 px (default: 0) |
| Enable horizontal padding | Adds horizontal padding inside the container | Checkbox (default: false) |
| Enable vertical padding | Adds vertical padding inside the container | Checkbox (default: false) |
| Enable margin | Adds margin around the container | Checkbox (default: false) |
| Gap size | Spacing between child blocks | None, Default (default), Xs, Sm, Md, Lg, Xl |
| Color scheme | Controls the background color scheme | Body (default), Neutral, Accent 1, Accent 2, Accent 3, Shade 1, Shade 2, Shade 3, Primary, Secondary, Tertiary, Blur, Transparent |
| Border color | Controls the border color | Body, Subtle (default), Strong, Primary, Secondary, Tertiary, None. Visible when border position is not empty |
| Enable color difference | Applies color blend mode for overlay effects | Checkbox (default: false) |
| Border position | Controls which sides have borders | None (default), Top, Bottom, Left, Right, Top and bottom, Left and right, All |
| Radius | Controls the border radius | None, Default (default), Sm, Md, Lg, Xl, 2xl, Full |
| Enable crop | Clips content that overflows the container | Checkbox (default: true) |
| Width | Controls the width of the container | 5 - 100 % (default: 100) |
| Minimum height | Minimum height of the container | 0 - 1200 px (default: 0). Visible when enable height fill is false |
| Enable height fill | Fills the container to the height of the parent | Checkbox (default: true) |
| Enable overlay | Positions the container as an absolute overlay | Checkbox (default: false) |
| Show on hover | Only displays the container on hover | Checkbox (default: false) |
| Enable block elevation | Increases z-index for sticky positioning | Checkbox (default: false). Visible when enable sticky layout is true |
| Enable sticky layout | Makes the container stick to viewport while scrolling | Checkbox (default: false) |
| Sticky position | Position where the container sticks | None (default), Top, Bottom. Visible when enable sticky layout is true |
| Vertical alignment | Controls vertical alignment of content | Top (default), Middle, Bottom |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |
| Scroll animation | Adds scroll-based animations to the block | None (default), Fade, Slide up, Slide down, Slide left, Slide right, Zoom |


# Product media


## Overview

A versatile product media block that renders product images or videos with extensive customization options. Features include hover effects with secondary media, aspect ratio control, flexible padding and spacing, comprehensive color schemes, and responsive visibility settings. The block automatically detects and handles both image and video media types from the product's media collection.


## Common use cases

- Ensure product has at least one media item before using this block
- Use hover effects only when product has multiple media items
- Consider aspect ratio settings based on your design system (square, video, portrait)
- Choose object-fit based on content: 'contain' for products that should be fully visible, 'cover' for decorative images
- Configure appropriate padding based on the block's container context
- Use color schemes that contrast well with your product images
- Test hover effects on touch devices to ensure good mobile experience
- Place this block early in product layouts for better perceived performance


## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Product | Select the product to display media for | Product picker |
| Show second image on hover | Displays the second product image/video when hovering over the first | Checkbox (default: true) |
| Enable horizontal padding | Adds horizontal padding around the media | Checkbox (default: false) |
| Enable top padding | Adds top padding around the media | Checkbox (default: false) |
| Enable bottom padding | Adds bottom padding around the media | Checkbox (default: false) |
| Color scheme | Controls the background and text color combination | Body, Neutral, Accent 1 (default), Accent 2, Accent 3, Shade 1, Shade 2, Shade 3, Primary, Secondary, Tertiary, Blur |
| Border color | Controls the border color | Body, Subtle (default), Strong, Primary, Secondary, Tertiary, None. Visible when border position is not empty |
| Border position | Position of borders on the media container | None (default), Top, Bottom, Left, Right, Top and bottom, Left and right, All |
| Enable aspect ratio | Enforces a specific aspect ratio for the media | Checkbox (default: false) |
| Show entire image | Uses object-contain instead of object-cover to show full image | Checkbox (default: true). Visible when enable aspect ratio is true |
| Aspect ratio | Controls the aspect ratio of the media | Square, Landscape, Portrait, None. Visible when enable aspect ratio is true |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |


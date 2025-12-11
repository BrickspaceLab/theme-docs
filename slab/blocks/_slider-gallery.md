# Slider gallery

## Block limitations

This is a private block and can only be used within specific parent blocks. It is designed to work exclusively within the `layout__slider` block.

## Overview

A product media gallery component that displays a collection of media items (images, videos, 3D models) in a slider format. This block is designed to work within a slider section, supporting responsive layouts and various media types from a product.

## Common use cases

- Best used within a slider section for product galleries
- Configure appropriate widths based on your layout needs
- Consider enabling zoom functionality for product images when detail viewing is important
- Use in conjunction with navigation controls for better user experience

## Child blocks

This block does not support child blocks.

## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Show variant images | Shows variant-specific images in the gallery | Checkbox (default: false) |
| Product | Product to display media from | Product picker |
| Item count | Number of media items to display | Number (default: 7) |
| Width mobile | Width of each slider item on mobile | 5 - 100 % (default: 80) |
| Width desktop | Width of each slider item on desktop | 5 - 100 % (default: 40) |
| Color scheme | Controls the background color scheme | Body (default), Neutral, Accent 1, Accent 2, Accent 3, Shade 1, Shade 2, Shade 3, Primary, Secondary, Tertiary, Blur, Transparent |
| Border color | Controls the border color | Body, Subtle (default), Strong, Primary, Secondary, Tertiary, None. Visible when border position is not empty |
| Border position | Controls which sides have borders | None (default), Top, Bottom, Left, Right, Top and bottom, Left and right, All |
| Enable aspect ratio | Maintains a consistent aspect ratio for media | Checkbox (default: false) |
| Show entire image | Shows the full image without cropping | Checkbox (default: true). Visible when enable aspect ratio is true |
| Aspect ratio | Aspect ratio for the media container | Square, Landscape, Portrait, None. Visible when enable aspect ratio is true |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |


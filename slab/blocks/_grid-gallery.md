# Product gallery

## Overview

A grid gallery block that displays media from a selected product. It iterates through the selected product's media to display images, videos, external videos, and 3D models. The block is highly customizable, supporting various styling options including color schemes, border configurations, and responsive visibility settings.

## Block limitations

This is a private block. It is intended for use only within specific parent blocks and should not be added directly to sections.

## Common use cases

- Always select a product in the theme editor to populate the gallery with media
- Adjust item_count to control the number of media items displayed in the gallery
- Utilize enable_aspect_ratio and aspect_ratio settings to maintain consistent media proportions across different devices
- Experiment with color_scheme, color_border, and border_position for visual customization to match the theme's aesthetic
- Use visibility options to create responsive layouts, showing different gallery configurations on mobile and desktop
- Enable variant images to show different images based on selected product variants

## Child blocks

This block has no nested child blocks. Media is automatically rendered from the selected product.

## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Enable variant images | Shows different images based on selected product variants | Checkbox (default: false) |
| Product | Select the product to display media from | Product picker |
| Item count | Number of media items to display (0 = all media) | Number input (default: 7) |
| Color scheme | Controls the background and text colors | Body (default), Neutral, Accent 1, Accent 2, Accent 3, Shade 1, Shade 2, Shade 3, Primary, Secondary, Tertiary, Blur, Transparent |
| Color border | Controls the border color | Body, Subtle (default), Strong, Primary, Secondary, Tertiary, None. Visible when border position is not blank |
| Border position | Controls where borders appear | None (default), Top, Bottom, Left, Right, Top and bottom, Left and right, All |
| Enable aspect ratio | Maintains consistent aspect ratio for all media items | Checkbox (default: false) |
| Show entire image | Displays entire image without cropping | Checkbox (default: true). Visible when enable aspect ratio is true |
| Aspect ratio | Aspect ratio for media items | Square, Landscape, Portrait, None. Visible when enable aspect ratio is true |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |


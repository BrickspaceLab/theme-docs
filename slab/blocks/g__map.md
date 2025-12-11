# Map

## Overview

A customizable store locator block that displays a map with markers for each store location. The block supports dynamic map rendering with Mapbox and static map rendering with an image. It also includes an accordion for each store location with details and a button to fly to the store.

## Common use cases

- Configure Mapbox API key in theme settings before adding this block
- Display store locations with interactive maps
- Use dynamic maps for better user experience or static images for simplicity
- Add location details and information through map item blocks

## Child blocks

This block includes the following nested blocks:

- Map item

## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Enable dynamic map | Enables interactive Mapbox map instead of static image | Checkbox (default: true) |
| Image map | Static map image (used when dynamic map is disabled) | Image picker. Visible when enable dynamic map is false |
| Color scheme | Controls the background and text colors | Body (default), Neutral, Accent 1, Accent 2, Accent 3, Shade 1, Shade 2, Shade 3, Primary, Secondary, Tertiary, Blur, Transparent |
| Color border | Controls the border color | Body (default), Subtle (default), Strong, Primary, Secondary, Tertiary, None. Visible when border position is not blank |
| Border position | Controls where borders appear | None (default), Top, Bottom, Left, Right, Top and bottom, Left and right, All |
| Map style | Mapbox map style | Standard, Dark, Light (default) |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |


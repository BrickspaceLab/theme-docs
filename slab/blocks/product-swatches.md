# Swatches

## Overview

A customizable product variant swatches block that displays color and other option swatches for products. Automatically detects color-type options (supporting multiple languages including color, colour, colore, farbe, couleur) and displays either custom uploaded swatch images or automatic Shopify swatches. Supports both Shopify's native swatch system and fallback asset-based swatch images for enhanced customization.

## Common use cases

- Upload custom swatch images to theme assets with naming pattern 'swatch-{variant-handle}.jpg'
- Set appropriate swatch limits based on available space and design context
- Use smaller swatch sizes (8-16px) for product cards, larger sizes (24-44px) for product pages
- Consider enabling tooltips for better user experience, especially with smaller swatch sizes
- Configure padding options based on the container context where swatches will be displayed
- Test with products that have many variants to ensure the "+N" remaining indicator displays properly

## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Product | Select the product to display swatches for | Product picker |
| Swatch size | Size of individual swatch previews | 8 - 44 px (default: 16) |
| Swatch limit | Maximum number of swatches to display before showing "+N" indicator | 1 - 20 (default: 6) |
| Swatch radius | Controls the border radius of swatches | None, Default, SM, MD, LG, XL, 2XL, Full (default) |
| Show tooltip | Displays tooltip on hover showing option value | Checkbox (default: true) |
| Enable horizontal padding | Adds horizontal padding around the swatches | Checkbox (default: false) |
| Enable top padding | Adds top padding around the swatches | Checkbox (default: false) |
| Enable bottom padding | Adds bottom padding around the swatches | Checkbox (default: false) |
| Horizontal alignment | Controls horizontal alignment of swatches | Left (default), Center, Right |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |


# Slider products

## Block limitations

This is a private block and can only be used within specific parent blocks. It is designed to work exclusively within the `layout__slider` block.

## Overview

A product slider component designed to display a collection of products within the layout__slider.liquid container. This block renders individual product items in a horizontally scrollable slider format with responsive sizing and customizable gap spacing.

## Common use cases

- Use for featuring product collections in a horizontal slider format
- Adjust width settings based on how many products you want visible at once
- Consider mobile experience when setting width values
- Use tag filtering to create themed or curated product collections

## Child blocks

This block does not support child blocks.

## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Collection | Collection to display products from | Collection picker |
| Item count | Number of products to display | Number (default: 7) |
| Filter by tag | Filter products by a specific tag | Text input |
| Show products in cart | Displays products even if they're already in the cart | Checkbox (default: true) |
| Width mobile | Width of each slider item on mobile | 5 - 100 % (default: 80) |
| Width desktop | Width of each slider item on desktop | 5 - 100 % (default: 20) |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |


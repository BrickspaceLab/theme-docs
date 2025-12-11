# Recently viewed

## Overview

A grid block that displays the recently viewed products in a grid layout. Uses Alpine.js to display products from the recently viewed products store.

## Block limitations

This is a private block. It is intended for use only within specific parent blocks and should not be added directly to sections.

## Common use cases

- Display recently viewed products to encourage customers to return to products they've seen
- Adjust item count based on available space in your layout
- Use responsive visibility to show different counts on mobile vs desktop
- Product cards are dynamically loaded to prevent layout shifts

## Child blocks

This block includes the following nested blocks:

- Product card (dynamically loaded)

## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Item count | Maximum number of recently viewed products to display | Number input (default: 5) |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |


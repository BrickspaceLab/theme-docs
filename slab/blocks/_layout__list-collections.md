# Collections grid

## Block limitations

This is a private block and can only be used within specific parent blocks. It is designed to work exclusively within collection list templates.

## Overview

A block for displaying paginated collections in a customizable grid layout with configurable columns, spacing, and styling. This block supports collection list templates.

## Common use cases

- Adjust items_per_page based on your store's needs
- Set appropriate row_desktop and row_mobile values for responsive design

## Child blocks

This block includes the following nested blocks:

- Grid paginate item blocks
- Container blocks (for top bar, sidebars, bottom bar)
- Pagination block

## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Items per page | Number of collections per page | 1 - 32 (default: 10) |
| Top spacing | Spacing above the grid | 0 - 300 px (default: 0) |
| Bottom spacing | Spacing below the grid | 0 - 300 px (default: 0) |
| Enable horizontal padding | Adds horizontal padding around the grid | Checkbox (default: false) |
| Gap size | Spacing between grid items | None, Default (default), Xs, Sm, Md, Lg, Xl |
| Border color | Controls the border color | Subtle (default), Strong |
| Border position | Controls which sides have borders | None (default), Top, Bottom, Top and bottom |
| Row desktop | Number of columns on desktop | 1 - 8 (default: 5) |
| Row mobile | Number of columns on mobile | 1 - 3 (default: 2) |
| Enable margin | Adds margin around the grid | Checkbox (default: false) |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |


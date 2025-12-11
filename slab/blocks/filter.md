# Filter


## Overview

A comprehensive filtering system for collection and search pages that provides customers with sorting options and advanced filtering capabilities. The block supports multiple filter types including boolean filters, list filters, and price range sliders with an accordion-style interface for organized presentation.


## Common use cases

- Ensure JavaScript functions (handleFilterChange, handleFilterDeleteAll, handlePriceFilterChange) are implemented for full functionality
- Configure border styling and internal padding based on your theme's design system
- Use appropriate gap sizes to maintain visual hierarchy between filter groups
- Test price range filters with your currency formatting and decimal handling
- Consider the number of filter options when deciding on swatch vs standard presentation
- Place this block in collection and search templates for optimal filtering experience


## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Enable filters | Enable or disable the filter functionality | Checkbox (default: true) |
| Enable sorting | Enable or disable sorting options | Checkbox (default: true) |
| Layout | Controls the filter container layout | Stacked (default), Inline |
| Top spacing | Spacing above the filter container | 0 - 30 px (default: 0) |
| Bottom spacing | Spacing below the filter container | 0 - 30 px (default: 0) |
| Enable horizontal padding | Adds horizontal padding around the container | Checkbox (default: false) |
| Enable internal padding | Adds internal padding to filter items | Checkbox (default: false). Visible when container layout is "stacked" |
| Gap size | Spacing between filter items | None (default), Default, Xs, Sm, Md, Lg, Xl |
| Button color | Color scheme for filter buttons in inline layout | Primary, Secondary, Tertiary, Neutral, Plain (default), Outline, Inverted outline, Blur, Link, Inverted link. Visible when container layout is "inline" |
| Button size | Size of filter buttons in inline layout | Extra small, Small (default), Standard, Large. Visible when container layout is "inline" |
| Border color | Color of borders around the filter container | Body, Subtle (default), Strong, Primary, Secondary, Tertiary, None. Visible when container border position is not empty and container layout is "stacked" |
| Border position | Position of borders on the filter container | None (default), Top, Bottom, Left, Right, Top and bottom, Left and right, All. Visible when container layout is "stacked" |
| Open filters | Comma-separated list of filter labels to open by default | Text input. Visible when container layout is "stacked" |
| Filter limit | Maximum number of filter options to display before showing "Show more" | Number input (default: 10) |
| Layout | Controls the layout of filter items | Stacked (default), Grid |
| Desktop rows | Number of columns per row on desktop | 1 - 4 (default: 2). Visible when items layout is "grid" |
| Mobile rows | Number of columns per row on mobile | 1 - 4 (default: 1). Visible when items layout is "grid" |
| Show filter count | Display the count of items for each filter option | Checkbox (default: true) |
| Show filter swatches | Display color/image swatches for filter options | Checkbox (default: true) |
| Swatch size | Size of color/image swatches | 8 - 256 px (default: 16). Visible when show filter swatches is true |
| Swatch radius | Border radius for color/image swatches | None, Default, Sm, Md, Lg, Xl, 2xl, Full (default). Visible when show filter swatches is true |
| Border color | Color of borders around filter items | Body, Subtle, Strong, Primary, Secondary, Tertiary, None (default). Visible when container layout is "stacked" |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |


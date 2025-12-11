# Buy buttons


## Overview

A comprehensive product purchase form block that handles variant selection, quantity input, and cart actions. The block dynamically displays different button states based on product availability and option selection, including "Choose Options", "Sold Out", "Unavailable", and "Add to Cart" states. Supports optional quantity input, dynamic checkout buttons, and real-time price display.


## Common use cases

- Ensure all product options are configured before adding this block
- Use inline layout only when horizontal space is sufficient for both quantity and button
- Enable quantity input for products that customers typically buy in bulk
- Configure appropriate button colors to match your theme's design system
- Test with products that have multiple variants to ensure proper option selection flow
- Consider enabling dynamic checkout for improved conversion rates


## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Product | Select the product to display buy buttons for | Product picker |
| Dynamic label | Custom label for the add to cart button (e.g., "Pre-order") | Rich text input. Visible when enable dynamic label is true |
| Enable dynamic label | Replaces "Add to cart" with custom label text | Checkbox (default: false) |
| Enable quantity input | Displays a quantity selector input field | Checkbox (default: false) |
| Enable dynamic checkout | Displays dynamic checkout buttons (Shop Pay, Apple Pay, etc.) | Checkbox (default: true) |
| Show price | Displays the product price on the add to cart button | Checkbox (default: true) |
| Show gift card form | Displays form fields for gift card recipient information | Checkbox (default: false) |
| Enable horizontal padding | Adds horizontal padding around the form | Checkbox (default: false) |
| Enable top padding | Adds top padding around the form | Checkbox (default: false) |
| Enable bottom padding | Adds bottom padding around the form | Checkbox (default: false) |
| Gap size | Spacing between form elements | None, Default (default), Xs, Sm, Md, Lg, Xl |
| Main button color | Color scheme for the add to cart button | Primary (default), Secondary, Tertiary, Neutral, Plain, Outline, Inverted outline, Blur, Link, Inverted link |
| Disabled button color | Color scheme for disabled/placeholder buttons | Primary, Secondary, Tertiary, Neutral, Plain (default), Outline, Inverted outline, Blur, Link, Inverted link |
| Dynamic checkout button color | Color scheme for dynamic checkout buttons | Primary, Secondary, Tertiary, Neutral, Plain (default) |
| Button size | Controls the size of buttons | Extra small, Small, Standard (default), Large |
| Quantity input | Style of the quantity input field | Default (default), Minimal. Visible when enable quantity input is true |
| Layout | Controls the layout of quantity and button | Stacked (default), Inline |
| Enable full width | Makes buttons span the full width of the container | Checkbox (default: false) |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |


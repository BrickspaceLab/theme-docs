# Popup


## Overview

A customizable popup modal component that displays content in an overlay triggered by a button. Provides smooth animations, responsive behavior, and extensive styling options through block settings.


## Common use cases

- Use semantic HTML within popup content for better accessibility
- Keep popup content concise to avoid overwhelming users
- Consider mobile viewports when designing popup content
- Test keyboard navigation and screen reader compatibility
- Use appropriate color contrast for overlay background


## Child blocks

This block includes the following nested blocks:

- Container (for popup content)


## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Overlay preset | Select a preset overlay ID or use a custom one | Account, Search, Menu, Primary cart, Alternative cart, Age verification, Quick buy, Quick edit, Custom (default) |
| Overlay ID | Custom identifier for the overlay (used to trigger it programmatically) | Text input. Visible when overlay preset is "Custom" |
| Show close button | Displays a close button in the popup | Checkbox (default: false) |
| Enable full background | Makes the popup background cover the entire viewport | Checkbox (default: false) |
| Color scheme | Controls the background and text color combination | Body, Neutral, Accent 1 (default), Accent 2, Accent 3, Shade 1, Shade 2, Shade 3, Primary, Secondary, Tertiary, Blur, Transparent |
| Border color | Controls the border color | Subtle (default), Strong, None |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |


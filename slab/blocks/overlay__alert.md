# Alert


## Overview

An alert overlay component that displays content in a floating panel that can be positioned at different corners of the screen. Supports auto-close functionality with visual progress indicator, customizable appearance, and responsive behavior.


## Common use cases

- Use for temporary notifications, messages, or calls-to-action
- Keep content concise as the alert has limited space
- Consider accessibility when choosing colors and auto-close timing
- Display important announcements or promotional messages
- Provide user feedback for actions


## Child blocks

This block includes the following nested blocks:

- Container (for alert content)


## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Overlay preset | Select a preset overlay ID or use a custom one | Account, Search, Menu, Primary cart, Alternative cart, Age verification, Form response, Discount, Error, Quick buy, Quick edit, Custom (default) |
| Overlay ID | Custom identifier for the overlay (used to trigger it programmatically) | Text input. Visible when overlay preset is "Custom" |
| Show close button | Displays a close button in the alert | Checkbox (default: false) |
| Color scheme | Controls the background and text color combination | Body, Neutral, Accent 1 (default), Accent 2, Accent 3, Shade 1, Shade 2, Shade 3, Primary, Secondary, Tertiary, Blur, Transparent |
| Border color | Controls the border color | Subtle (default), Strong, None |
| Enable auto close | Automatically closes the alert after a set duration | Checkbox (default: false) |
| Auto close duration | Time before the alert automatically closes | 1 - 10 s (default: 3). Visible when enable auto close is true |
| Horizontal position | Position of the alert along the horizontal axis | Left, Right (default) |
| Vertical position | Position of the alert along the vertical axis | Top (default), Bottom |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |


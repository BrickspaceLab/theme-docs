# Logo


## Overview

Displays the store logo with responsive sizing for desktop and mobile devices. The component renders either an uploaded logo image or falls back to the shop name as text if no image is provided. The logo is fully customizable with options for height adjustments on different devices, horizontal alignment, padding, and visibility controls across breakpoints.


## Common use cases

- Upload a logo with transparent background for best results
- Adjust desktop and mobile logo heights to maintain proper proportions and readability
- Consider logo placement within the overall header layout when choosing alignment
- Use text fallback when logo image is not available


## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Logo | Upload a logo image | Image picker. Visible when show image is true |
| URL | Link destination when logo is clicked | URL input (default: /) |
| Text | Text to display if no logo image is provided | Text input. Visible when show image is false |
| Show image | Toggle between logo image and text | Checkbox (default: false) |
| Desktop logo height | Height of the logo on desktop devices | 10 - 200 px (default: 24) |
| Mobile logo height | Height of the logo on mobile devices | 10 - 200 px (default: 24) |
| Enable horizontal padding | Adds horizontal padding around the logo | Checkbox (default: false) |
| Font family | Controls the font family used for text logo | Standard, Heading (default), Subheading, Accent. Visible when font size contains 'type--' or font size is "custom" |
| Font size | Controls the font size of text logo | Smaller, Small, Default, Big, Bigger (default), Heading 1, Heading 2, Heading 3, Heading 4, Heading 5, Heading 6, Custom |
| Size | Custom font size when using custom typography | 4 - 400 px (default: 16). Visible when font size is "custom" |
| Line height | Custom line height when using custom typography | 100 - 300 % (default: 150). Visible when font size is "custom" |
| Letter spacing | Custom letter spacing when using custom typography | -3 - 3 rem (default: 0). Visible when font size is "custom" |
| Horizontal alignment | Controls horizontal alignment | Left (default), Center, Right |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |


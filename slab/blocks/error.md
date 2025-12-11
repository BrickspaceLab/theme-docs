# Error message


## Overview

A dynamic error message display block that renders error text from an Alpine.js store. Provides customizable styling options including text color, font family, size, alignment, and responsive visibility controls.


## Common use cases

- Enable max_width (default: true) for better readability of error messages
- Consider the context where errors will appear when choosing text color and size
- Use appropriate padding settings based on surrounding content
- Display validation and system error messages throughout your theme


## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Enable horizontal padding | Adds horizontal padding around the content | Checkbox (default: false) |
| Enable top padding | Adds top padding around the content | Checkbox (default: false) |
| Enable bottom padding | Adds bottom padding around the content | Checkbox (default: false) |
| Text color | Controls the text color | Default (default), Alternative, Primary background, Primary foreground, Secondary background, Secondary foreground, Tertiary background, Tertiary foreground, Neutral background, Neutral foreground, Shade, Error, Success |
| Font family | Controls the font family used for the text | Standard, Heading, Subheading, Accent. Visible when font size contains 'type--' |
| Font size | Controls the font size of the text | Smaller, Small, Default (default), Big, Bigger, Heading 1, Heading 2, Heading 3, Heading 4, Heading 5, Heading 6 |
| Horizontal alignment | Controls horizontal text alignment | Left (default), Center, Justify, Right |
| Enable max width | Limits the maximum width of the text content | Checkbox (default: true) |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |


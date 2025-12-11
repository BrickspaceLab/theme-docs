# Rich text


## Overview

A flexible rich text content block that allows for formatted text content with customizable text color, alignment, and responsive visibility options.


## Common use cases

- Use for any formatted text content like paragraphs, headings, lists
- Consider text color contrast when using force light/dark options
- Use visibility options to create different content for mobile/desktop
- Default text alignment is left-aligned for better readability


## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Content | The main text content to display | Richtext input |
| Enable horizontal padding | Adds horizontal padding around the content | Checkbox (default: false) |
| Enable top padding | Adds top padding around the content | Checkbox (default: false) |
| Enable bottom padding | Adds bottom padding around the content | Checkbox (default: false) |
| Text color | Controls the text color | Default (default), Alternative, Primary background, Primary foreground, Secondary background, Secondary foreground, Tertiary background, Tertiary foreground, Neutral background, Neutral foreground, Shade |
| Font family | Controls the font family used for the text | Standard (default), Heading, Subheading, Accent. Visible when font size contains 'type--' or font size is "custom" |
| Font size | Controls the font size of the text | Smaller, Small, Default (default), Big, Bigger, Heading 1, Heading 2, Heading 3, Heading 4, Heading 5, Heading 6, Custom |
| Size | Custom font size when using custom typography | 4 - 200 px (default: 16). Visible when font size is "custom" |
| Line height | Custom line height when using custom typography | 100 - 300 % (default: 150). Visible when font size is "custom" |
| Letter spacing | Custom letter spacing when using custom typography | -3 - 3 rem (default: 0). Visible when font size is "custom" |
| Horizontal alignment | Controls horizontal text alignment | Left (default), Center, Justify, Right |
| Enable max width | Limits the maximum width of the text content | Checkbox (default: true) |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |
| Scroll animation | Adds scroll-based animations to the block | None (default), Fade, Slide up, Slide down, Slide left, Slide right, Zoom |


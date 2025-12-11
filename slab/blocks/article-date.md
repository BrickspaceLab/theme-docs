# Article date


## Overview

A configurable block that renders the published date of the nearest article using the 'abbreviated_date' format; supports alignment, typography, color, spacing, max width, visibility, and custom size controls via block settings; intended for use inside article cards, article templates, or blog listings; uses Tailwind utility classes and respects Theme Editor preview constraints.


## Common use cases

- Place near other article metadata (author, tags) for consistent hierarchy
- Prefer the default or smaller type sizes for subtle metadata
- Use custom size sparingly; favor predefined sizes for consistency
- Consider enabling max width to maintain readability in wide layouts


## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Enable horizontal padding | Adds horizontal padding around the date | Checkbox (default: false) |
| Enable top padding | Adds top padding around the date | Checkbox (default: false) |
| Enable bottom padding | Adds bottom padding around the date | Checkbox (default: false) |
| Text color | Controls the text color | Default (default), Alternative, Primary background, Primary foreground, Secondary background, Secondary foreground, Tertiary background, Tertiary foreground, Neutral background, Neutral foreground, Shade |
| Font family | Controls the font family used for the date | Standard, Heading, Subheading, Accent. Visible when font size contains 'type--' |
| Font size | Controls the font size of the date | Smaller, Small, Default (default), Big, Bigger, Heading 1, Heading 2, Heading 3, Heading 4, Heading 5, Heading 6 |
| Horizontal alignment | Controls horizontal alignment | Left (default), Center, Right |
| Enable max width | Limits the maximum width of the date text | Checkbox (default: true) |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |


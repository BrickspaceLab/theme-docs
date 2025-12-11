# Table

## Overview

A flexible container component that provides customizable table layout options for child blocks. Allows merchants to add multiple table items with customizable columns.

## Common use cases

- Create comparison tables for products or services
- Display structured data in rows and columns
- Use column highlighting to emphasize specific columns
- Configure custom column widths for optimal content display

## Child blocks

This block includes the following nested blocks:

- Table row

## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Column headings | Comma-separated list of column header labels | Text input |
| Color scheme | Controls the background and text colors | Body (default), Neutral, Accent 1, Accent 2, Accent 3, Shade 1, Shade 2, Shade 3, Primary, Secondary, Tertiary, Blur, Transparent |
| Enable column highlight | Highlights a specific column with a different color scheme | Checkbox (default: false) |
| Column color scheme | Color scheme for the highlighted column | Body (default), Neutral, Accent 1, Accent 2, Accent 3, Shade 1, Shade 2, Shade 3, Primary, Secondary, Tertiary (default), Blur, Transparent. Visible when enable column highlight is true |
| Highlighted column | Column number to highlight (1-based index) | 0 - 10 (default: 2). Visible when enable column highlight is true |
| Enable horizontal padding | Adds horizontal padding around the table | Checkbox (default: false) |
| Top spacing | Padding space at the top of the table | 0 - 300 px (default: 0) |
| Bottom spacing | Padding space at the bottom of the table | 0 - 300 px (default: 0) |
| Font family | Controls the font family for table content | Standard (default), Heading, Subheading, Accent. Visible when font size contains type-- |
| Font size | Controls the font size for table content | Smaller, Small, Default (default), Big, Bigger, Heading 1, Heading 2, Heading 3, Heading 4, Heading 5, Heading 6 |
| Table layout | Controls how table columns are sized | Auto, Fixed (default), Custom |
| Column widths | Comma-separated list of custom column widths (e.g., "30%, 40%, 30%") | Text input. Visible when table layout is custom |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |
| Scroll animation | Adds scroll-triggered animations | None (default), Fade, Slide up, Slide down, Slide left, Slide right, Zoom |


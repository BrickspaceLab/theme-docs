# Video

## Overview

A customizable video block component that supports both native and custom video controls. Provides flexible styling options including color schemes, button styles, and layout controls.

## Common use cases

- Use custom controls for branded experience
- Consider mobile bandwidth when autoplaying videos
- Adjust width for different layout contexts
- Configure autoplay and loop settings for background videos
- Customize play button styling to match your theme

## Child blocks

This block includes the following nested blocks:

- Container (for play label)

## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Video | Select the video to display | Video picker |
| Autoplay video | Automatically plays the video when loaded | Checkbox (default: true) |
| Loop video | Loops the video continuously | Checkbox (default: true) |
| Default video controls | Shows native browser video controls | Checkbox (default: false) |
| Custom video controls | Shows custom play/pause and mute controls | Checkbox (default: true) |
| Enable horizontal padding | Adds horizontal padding around the video | Checkbox (default: false) |
| Enable top padding | Adds top padding around the video | Checkbox (default: false) |
| Enable bottom padding | Adds bottom padding around the video | Checkbox (default: false) |
| Color scheme | Controls the background and text colors | Body, Neutral, Accent 1 (default), Accent 2, Accent 3, Shade 1, Shade 2, Shade 3, Primary, Secondary, Tertiary, Blur |
| Color border | Controls the border color | Subtle (default), Strong, None |
| Width | Width of the video as percentage | 5 - 100 % (default: 100) |
| Min width | Minimum width in pixels | 5 - 500 px (default: 500) |
| Radius | Border radius for the video container | None, Default (default), SM, MD, LG, XL, 2XL, Full |
| Horizontal alignment | Controls horizontal alignment of the video | Left (default), Center, Right |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |


# Share

## Overview

A customizable share component that allows users to easily share content to social media platforms. Features a share button with dynamic text feedback and supports native sharing on supported devices.

## Common use cases

- Enable sharing to Facebook, Twitter/X, Pinterest, and LinkedIn
- Use the navigator.share API for native sharing on supported devices
- Include a fallback dropdown for manual sharing options
- Ensure the canonical URL is correctly set for accurate sharing
- Customize button styles through theme settings for consistency

## Child blocks

This block includes the following nested blocks:

- Container (for share label)
- Container (for share content)

## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Enable Facebook share | Shows Facebook share button | Checkbox (default: true) |
| Enable X Twitter share | Shows X/Twitter share button | Checkbox (default: true) |
| Enable Pinterest share | Shows Pinterest share button | Checkbox (default: true) |
| Enable LinkedIn share | Shows LinkedIn share button | Checkbox (default: true) |
| Enable horizontal padding | Adds horizontal padding around the share component | Checkbox (default: false) |
| Enable top padding | Adds top padding around the share component | Checkbox (default: false) |
| Enable bottom padding | Adds bottom padding around the share component | Checkbox (default: false) |
| Width | Width of the dropdown menu | 100 - 400 px (default: 250) |
| Vertical direction | Direction the dropdown opens | Down, Up (default) |
| Horizontal position | Horizontal alignment of dropdown relative to trigger | Left (default), Center, Right |
| Horizontal alignment | Controls alignment of the share trigger button | Left (default), Center, Right |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |


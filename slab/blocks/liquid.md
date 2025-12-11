# Liquid


## Overview

A flexible custom liquid code block that allows merchants to add custom liquid code to their theme with customizable styling and responsive visibility options.


## Common use cases

- Use for custom liquid code snippets, variables, or logic
- Consider text color contrast when using force light/dark options
- Use visibility options to create different content for mobile/desktop
- Test liquid code thoroughly before using in production
- Be cautious with liquid code that could break the theme


## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Liquid | Custom liquid code to execute | Liquid input (default: {{ shop.name }}) |
| Enable horizontal padding | Adds horizontal padding around the content | Checkbox (default: false) |
| Enable top padding | Adds top padding around the content | Checkbox (default: false) |
| Enable bottom padding | Adds bottom padding around the content | Checkbox (default: false) |
| Horizontal alignment | Controls horizontal text alignment | Left (default), Center, Justify, Right |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |


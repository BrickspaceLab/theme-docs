# Age verification form

## Overview

A customizable age verification block that prevents site access until users confirm they meet the minimum required age. Supports both birthdate verification and simple confirmation methods.

## Common use cases

- Set appropriate age requirements based on your products and local regulations
- Use the date verification method for stricter compliance needs
- Customize button styling to match your theme design
- Remember verified users between sessions using localStorage

## Child blocks

This block includes the following nested blocks:

- Button

## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Enable age verification | Enables the age verification form | Checkbox (default: false) |
| Age verification type | Select the verification method | Date (default), Confirmation |
| Age requirement | Minimum age required for access | 1 - 99 (default: 18) |
| Enable horizontal padding | Adds horizontal padding around the form | Checkbox (default: false) |
| Enable top padding | Adds top padding around the form | Checkbox (default: false) |
| Enable bottom padding | Adds bottom padding around the form | Checkbox (default: false) |
| Text color | Controls the text color for error messages | Default (default), Alternative, Primary background, Primary foreground, Secondary background, Secondary foreground, Tertiary background, Tertiary foreground, Neutral background, Neutral foreground, Shade |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |


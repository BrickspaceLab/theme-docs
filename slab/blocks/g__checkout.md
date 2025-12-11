# Checkout

## Overview

A checkout container block that displays a form with checkout button, only visible when cart has items. Handles checkout redirection and supports Alpine.js for interactivity.

## Common use cases

- Display checkout button in cart drawers or cart pages
- Only shows when cart has items (handled automatically)
- Customize through block settings rather than editing the liquid code directly
- Use with g__button blocks for checkout functionality

## Child blocks

This block includes the following nested blocks:

- Button

## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Enable horizontal padding | Adds horizontal padding around the checkout form | Checkbox (default: false) |
| Enable top padding | Adds top padding around the checkout form | Checkbox (default: false) |
| Enable bottom padding | Adds bottom padding around the checkout form | Checkbox (default: false) |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |


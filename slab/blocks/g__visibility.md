# Visibility

## Overview

A container block that controls content visibility based on screen size and customer status. Conditionally renders child blocks based on customer authentication state and screen size requirements.

## Common use cases

- Use for content that needs to be completely hidden from certain user groups
- Prefer this over CSS display:none for sensitive content
- Consider performance impact when hiding large content blocks
- Control visibility based on device type, customer status, or cart state

## Child blocks

This block includes the following nested blocks:

- All theme blocks
- App blocks

## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Device visibility | Controls visibility based on device type | All (default), Mobile only, Desktop only |
| Customer visibility | Controls visibility based on customer authentication and status | All (default), Logged out only, Any account, Approved account, B2B account |
| Cart visibility | Controls visibility based on cart state | All (default), Empty cart only, Not empty cart only |
| Scroll animation | Adds scroll-triggered animations | None (default), Fade, Slide up, Slide down, Slide left, Slide right, Zoom |


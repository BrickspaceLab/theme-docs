# Cart count


## Overview

Displays a cart count indicator that shows the current number of items in the cart. Can be displayed inline or as a floating badge with configurable position. The count is dynamically updated using Alpine.js.


## Common use cases

- For floating layout, adjust x/y positions to align properly with your cart icon
- Consider visibility settings for responsive designs when using multiple cart icons
- Display cart item count in headers or navigation areas
- Use as a badge overlay on cart icons


## Block settings

### Content

| Setting | Description | Options |
|---------|-------------|---------|
| Digit limit | Maximum number of digits to display before showing "+" suffix (e.g., 2 = "99+") | Number input (default: 2) |


### Color

| Setting | Description | Options |
|---------|-------------|---------|
| Button color | Color scheme for the cart count indicator | • Primary (default)<br>• Secondary<br>• Tertiary<br>• Neutral<br>• Plain<br>• Outline<br>• Inverted outline<br>• Blur<br>• Link<br>• Inverted link |


### Style

| Setting | Description | Options |
|---------|-------------|---------|
| Font family | Controls the font family used for the count | • Standard<br>• Heading<br>• Subheading<br>• Accent<br><br>Visible when font size contains 'type--' |
| Font size | Controls the font size of the count | • Smaller<br>• Small<br>• Default (default)<br>• Big<br>• Bigger<br>• Heading 1<br>• Heading 2<br>• Heading 3<br>• Heading 4<br>• Heading 5<br>• Heading 6 |
| Radius | Border radius for the count indicator | • None<br>• Default (default)<br>• SM<br>• MD<br>• LG<br>• XL<br>• 2XL<br>• Full |


### Layout

| Setting | Description | Options |
|---------|-------------|---------|
| Layout | Controls the layout of the count indicator | • Float<br>• Inline (default) |
| Horizontal position | Horizontal position as percentage (for float layout) | 0 - 100 % (default: 55)<br><br>Visible when layout is "float" |
| Vertical position | Vertical position as percentage (for float layout) | 0 - 100 % (default: 0)<br><br>Visible when layout is "float" |


### Display

| Setting | Description | Options |
|---------|-------------|---------|
| Visibility | Controls when the block is visible | • All (default)<br>• Mobile only<br>• Desktop only |

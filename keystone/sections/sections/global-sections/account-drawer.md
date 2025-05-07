# Account drawer

### Section overview

This section is responsible for rendering and managing the account drawer functionality which includes login forms, customer account information, orders, addresses, and customizable content blocks.

#### Common use cases

* Providing customers with access to their account information, orders, and addresses
* Creating personalized login/signup experiences for different user states
* Adding custom content and announcements visible only to specific customer segments
* Integrating B2B functionality with company locations and permissions

#### Usage tips

* Customize the color schemes to match your store's branding
* Use content blocks with different visibility settings to create personalized experiences
* Consider mobile responsiveness as the account drawer adapts differently on mobile (bottom drawer) vs desktop (right drawer)
* Avoid adding too many content blocks as this can make the account drawer feel cluttered

### Section settings

| Setting                   | Description                                                                        |
| ------------------------- | ---------------------------------------------------------------------------------- |
| Top bar color scheme      | Sets the background and text color for the top bar of the account drawer           |
| Top bar border color      | Controls the border color for the top section of the account drawer                |
| Main section color scheme | Sets the background and text color for the main content area of the account drawer |
| Main section border color | Controls the border color for the main content area of the account drawer          |

### Block settings

#### Announcement

This block allows you to add a prominent announcement message at the top of the account drawer.

Block limit: 1

| Setting              | Description                                                |
| -------------------- | ---------------------------------------------------------- |
| Content              | The text content of the announcement message               |
| Color scheme         | The background and text color for the announcement message |
| Horizontal alignment | Controls the alignment of the text (left, center, right)   |

#### Content

This block adds customizable content sections to the account drawer that can be configured to display based on customer login status.

Block limit: 15

| Setting              | Description                                                                                             |
| -------------------- | ------------------------------------------------------------------------------------------------------- |
| Visibility           | Controls when this content appears (always, logged out, logged in not approved, logged in and approved) |
| Heading              | The title text for the content block                                                                    |
| Content              | The main text content for the block                                                                     |
| Button label         | Text to display on the block's call-to-action button                                                    |
| URL                  | The destination link for the button                                                                     |
| Image                | The main image to display in the content block                                                          |
| Image background     | A background image to display behind the content                                                        |
| Video                | A video to display in the content block                                                                 |
| Enable autoplay      | Controls whether the video plays automatically                                                          |
| Enable mute toggle   | Adds a button to toggle video sound on/off                                                              |
| Enable loop          | Controls whether the video repeats after finishing                                                      |
| Minimum height       | Sets the minimum height for the content block in pixels                                                 |
| Enable padding       | Adds padding around the content block when enabled                                                      |
| Color scheme         | Sets the background and text color for the content block                                                |
| Text color           | Controls whether to use default, light, or dark text regardless of background                           |
| Border color         | Sets the border style around the content block                                                          |
| Button color         | Controls the appearance and style of the button                                                         |
| Enable gradient      | Adds a gradient effect to the background when enabled                                                   |
| Vertical alignment   | Controls the vertical positioning of content (top, middle, bottom)                                      |
| Horizontal alignment | Controls the horizontal positioning of content (left, center, justify, right)                           |
| Text position        | Controls whether text appears above or below the image/video                                            |

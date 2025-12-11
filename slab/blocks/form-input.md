# Input field


## Overview

A configurable form input block that renders different types of form inputs based on the selected input type, supporting text, textarea, email, checkbox, radio, select, date, file, and password input types.


## Common use cases

- Use appropriate input types for different data collection needs
- Provide clear labels and help text for better accessibility
- Consider required field settings based on form validation needs
- Create comprehensive forms by combining multiple input field blocks


## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Input type | Select the type of form input to display | Text, Textarea, Email, Checkbox, Radio, Select, Date, File, Password |
| Label | Label text for the input field | Text input |
| Placeholder | Placeholder text shown in the input | Text input. Visible when input type is not checkbox and input type is not radio |
| Help text | Additional help text displayed below the input | Rich text input. Visible when input type is not checkbox and input type is not radio |
| Options | Comma-separated list of options for select or radio inputs | Textarea input. Visible when input type is "select" or input type is "radio" |
| Accepted file types | File types accepted for file inputs | Text input (default: .jpg, .jpeg, .png, .pdf, .svg, .gif). Visible when input type is "file" |
| Enable multiple files | Allows multiple file selection for file inputs | Checkbox (default: false). Visible when input type is "file" |
| Enable required field | Marks the input as required | Checkbox (default: false) |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |


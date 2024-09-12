# Email Validation JavaScript

This project provides a simple email validation form using HTML, CSS, and JavaScript. It demonstrates how to validate an email address format in real-time and provide feedback to the user.

## Features

- **Real-Time Email Validation**: Validates the email format as the user types.
- **Visual Feedback**: Displays a success or error icon and message based on the email validity.
- **Responsive Design**: Centered form that adapts to different screen sizes.

## Demo

You can view a live demo of the email validation [here](https://emailvalidator1430.netlify.app/).

## Technologies Used

- **HTML**: Structure of the form and document.
- **CSS**: Styling and layout of the form.
- **JavaScript**: Functionality for real-time email validation.

## Installation

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/PrashanthEmmadi1430/email-validation.git
    ```

2. **Navigate to the Project Directory**:

    ```bash
    cd email-validation
    ```

3. **Open the `index.html` File**:

    Open the `index.html` file in your preferred web browser to view and test the email validation form.

## Code Overview

### HTML

- The form element with `id="form"` contains an email input field and a span for displaying validation messages.
- The `onkeydown` event triggers the validation function.

### CSS

- **General Styling**: Sets margin, padding, and font-family for the document.
- **Body Styling**: Centers the form both horizontally and vertically.
- **Form Styling**: Styles the email input field and manages the appearance of validation icons.
- **Validation Feedback**: Uses pseudo-elements to show validation icons based on the form's validity class.

### JavaScript

- **`validation()` Function**: 
  - Retrieves the email value and applies a regular expression pattern to check if it’s a valid email address.
  - Updates the form’s class and message based on the validation result.
  - Clears validation if the input is empty.

## How to Use

1. **Open the HTML File**: Open the `index.html` file in your web browser.
2. **Enter an Email Address**: As you type in the email input field, the form will validate the email format.
3. **View Feedback**: See real-time validation feedback including visual icons and messages.

## Contributions

Feel free to contribute by submitting issues or pull requests. If you have suggestions for improvements, please let us know!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please contact [prashanthemmadi6@gmail.com](prashanthemmadi6@gmail.com).

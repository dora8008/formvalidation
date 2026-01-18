# FV – Form Validation

A client-side form validation application built using **HTML, CSS, and JavaScript**.  
This project validates user inputs in real time using **regular expressions** and **DOM events**, providing clear and accessible feedback for better user experience.

## Features

- Real-time input validation
- Regex-based validation rules
- Required field checks
- Strong password policy enforcement
- Password visibility toggle (Show / Hide)
- Confirm password matching
- Optional phone number validation
- Terms & conditions acceptance check
- Accessible error messages
- Clean and responsive UI

## Validation Rules

- **Full Name**: Required, alphabetic characters only
- **Email**: Must follow valid email format
- **Password**:
  - Minimum 8 characters
  - At least one uppercase letter
  - At least one lowercase letter
  - At least one number
  - At least one special character
- **Confirm Password**: Must match the password
- **Phone Number (Optional)**:
  - Indian format supported (+91)
- **Terms Agreement**: Must be checked before submission

## Concepts Used

- HTML form elements
- CSS styling and layout
- JavaScript DOM manipulation
- Regular expressions (Regex)
- Event listeners (`input`, `blur`, `submit`)
- Client-side validation logic

## How It Works (Short)

As the user types, JavaScript listens to input events and validates each field using predefined regex rules. Error messages are displayed instantly, and the form submission is blocked until all required fields are valid.

## Project Structure

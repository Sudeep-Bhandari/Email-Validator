# Email Validator

A simple Python script for validating email addresses using regular expressions (`re` module). This tool helps verify if an email address is correctly formatted.

## Features

- Validates email addresses based on a regular expression pattern.
- Provides instant feedback on whether an email is valid or invalid.
- Simple and user-friendly command-line interface.

## Technologies Used

- **Python**: Core programming language.
- **`re` Module**: Used for regex-based email validation.

## Installation and Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Sudeep-Bhandari/Email-Validator.git
   
2. Navigate to the project directory:
   ```bash
   cd Email-Validator
   
3. Run the script:
   ```bash
   python Email-Validator.py
   
4. Validate emails:
  - Enter an email address when prompted to check its validity.
  - Type exit to quit the script.


## License
This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License. You are free to use, modify, and distribute it as per the license terms.

## Example Usage
   ```bash
   Welcome to Email Validator!
   Enter an email address to validate (or type 'exit' to quit): test@example.com
   'test@example.com' is a valid email address.

   Enter an email address to validate (or type 'exit' to quit): invalid-email
   'invalid-email' is NOT a valid email address.

   Enter an email address to validate (or type 'exit' to quit): exit
   Goodbye!

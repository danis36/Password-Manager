# MyPass Password Manager

A simple and secure password manager built with Python and Tkinter GUI.

## Features

- **Password Generation**: Automatically generates strong passwords with a mix of letters, numbers, and symbols
- **Secure Storage**: Saves website credentials locally in a text file
- **User-Friendly Interface**: Clean and intuitive GUI with logo branding
- **Clipboard Integration**: Generated passwords are automatically copied to clipboard
- **Input Validation**: Ensures no empty fields before saving credentials
- **Confirmation Dialog**: Asks for confirmation before saving new entries

## Requirements

- Python 3.x
- tkinter (usually comes with Python)
- pyperclip (`pip install pyperclip`)

## Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/mypass-password-manager.git
```

2. Install required dependencies:
```bash
pip install pyperclip
```

3. Make sure you have a `logo.png` file in the same directory as the script

## Usage

1. Run the application:
```bash
python password_manager.py
```

2. Enter the website name and your email/username
3. Either enter your own password or click "Generate Password" for a strong password
4. Click "Add" to save the credentials
5. All data is stored in `data.txt` file

## Security Note

This is a basic password manager for educational purposes. For production use, consider implementing encryption for stored passwords and additional security measure

## Contributing

Feel free to fork this project and submit pull requests for improvements.

## License

This project is open source and available under the [MIT License](LICENSE).# Password-Manager

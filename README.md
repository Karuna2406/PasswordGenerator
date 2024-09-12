# Password Generator 

## Overview

This Password Generator is a web application that allows users to generate strong, customizable passwords. Users can adjust the length and choose to include uppercase letters, lowercase letters, numbers, and symbols. The tool also features a simple interface, making it easy for anyone to create secure passwords quickly.

## Features

- **Customizable Passwords**: You can select the password length (between 4 and 20 characters) and toggle the inclusion of uppercase letters, lowercase letters, numbers, and symbols.
- **Clipboard Functionality**: One-click copy feature to easily copy the generated password to your clipboard.
- **Responsive Design**: Works well across devices, including desktops, tablets, and mobile phones.
- **Interactive Interface**: Simple UI with real-time password generation.

## How to Use

1. **Open the Application**: Load the HTML page in your browser.
2. **Adjust Settings**:
   - Set the password length by entering a number in the input field.
   - Use the checkboxes to include or exclude uppercase letters, lowercase letters, numbers, and symbols.
3. **Generate Password**: Click the "Generate Password" button to create a random password based on your selected settings.
4. **Copy Password**: Click the clipboard icon to copy the generated password to your clipboard for easy use.

## Files Included

1. **HTML File (`index.html`)**: The main structure of the password generator application.
2. **CSS File (`style.css`)**: Defines the layout and design of the application.
3. **JavaScript File (`script.js`)**: Contains the logic for generating the password and handling user interactions.

## Code Breakdown

- **HTML Structure**:
   - A simple layout with options to adjust password settings (length, character types) and buttons for generating and copying the password.
   - Utilizes FontAwesome for the clipboard icon.

- **CSS Design**:
   - Background color: `#3b3b98` for the main page, providing a sleek, modern look.
   - The password container and input areas have subtle shadows and a dark theme (`#23235b`) to enhance visual appeal.
   - Responsive styling ensures the app works well on various devices.

- **JavaScript Functionality**:
   - Generates random passwords based on user-selected criteria (length, character type).
   - Clipboard functionality to copy the generated password easily.
   - The app listens for user inputs (e.g., button clicks, checkbox selections) and dynamically updates the password.

## Example Usage

- To create a 16-character password that includes uppercase letters, lowercase letters, numbers, and symbols:
   1. Set the password length to 16.
   2. Ensure all checkboxes (uppercase, lowercase, numbers, symbols) are checked.
   3. Click "Generate Password."
   4. Copy the password by clicking the clipboard icon.


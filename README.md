# Secure Password Tool
A modern, user-friendly web app built with Streamlit that helps you generate secure passwords and evaluate password strength with real-time visual feedback and suggestions.

## Features

**Password Strength Meter**

Checks password based on:

- Minimum length (8 characters)

- Upper & lowercase characters

- Numbers (0–9)

- Special characters (!@#$%^&*)

- Displays a colored strength bar

- Provides suggestions for improvement

**Password Generator**

- Choose length (8 to 16 characters)

- Toggle inclusion of numbers and special characters

- Password history panel to keep track of generated passwords

**Light/Dark Theme Toggle**
Switch between Blue and Green themed modes via the sidebar

## Technologies Used
- Streamlit

- Python Standard Libraries:
string, random, re

- Custom CSS for UI theming

## Installation

1. **Clone the repository:**

  ```bash
    git clone https://github.com/Abdullah-Ikhlaq/password-toolkit.git
    cd password-toolkit
  ``` 

2. **Install the required packages**

Make sure you have Python installed. Then, install Streamlit using pip:
  ```bash
   pip install streamlit
  ```

3. **Run the app:**

Start the Streamlit server
 ```bash
  streamlit run app.py
  ```

This will open the application in your default web browser.

## File Structure

```bash
 password-toolkit/
 │
 ├── app.py               # Main Streamlit application
 ├── README.md            # Project documentation
 └── requirements.txt     # (Optional) Python dependencies
```

## Authors
Abdullah Ikhlaq
Zain ul Abideen
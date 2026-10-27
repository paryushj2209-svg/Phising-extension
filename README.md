# CMPE209FinalProject - Phising extension using LLM

Original repository: [https://github.com/Xainax/CMPE209FinalProject](https://github.com/Xainax/CMPE209FinalProject)

Requirement
   - NodeJS version v20.0.0 or greater
   - Python 3.12
- Build the backend:
  ```sh
        cd backend
        python3.12 -m venv venv
        source venv/bin/activate
        pip install -r requirements.txt
        export GEMINI_API_KEY="your-key"
        export GEMINI_MODEL="gemini-3.8-flash"
        python app.py
    ```

  On Windows PowerShell, use:

  ```powershell
  cd backend
  py -3.12 -m venv venv
  venv\Scripts\Activate.ps1
  pip install -r requirements.txt
  $env:GEMINI_API_KEY = "your-key"
  $env:GEMINI_MODEL = "gemini-3.8-flash"
  python app.py
  ```

- Build the extension:
    ```sh
        cd frontend/phishing-extension
        npm install
        npm run build
    ```

- Install the extension locally:
    - Step 1: Access the extension.
        - In Google Chrome browser tab bar, type chrome://extensions/
    - Step 2: Turn on developer mode:
        - Toggle on the developer mode located at the upper right of the extension window. This allow us to load the extension for testing purpose
    - Step 3: Load the unpacked extension.
        - After the developer mode is turned on, browser will show you the button upload extension. Simply click to the Load Unpacked button and navigate to the extension folder in the project to upload the extension.

# Final Demo/Presentation Video
https://drive.google.com/file/d/1da0vrgniRjeGQX0DhJtp49EqYFVWwu5Z/view?usp=drive_link

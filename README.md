# AutomateFormUploadOnMySuccess
A customizable script to upload all files (currently cover letters) from a given directory to Carleton Co-op site and constructs application packages from them.
# Selenium Coop Application

This Python script uses Selenium to automate the process of uploading cover letters and creating application packages on the Carleton University Co-op Portal , (https://mysuccess.carleton.ca/).

## Prerequisites

- [Python](https://www.python.org/downloads/) (>= 3.6)
- [ChromeDriver](https://sites.google.com/chromium.org/driver/) (Ensure it's in your system PATH)
- Selenium

## Installation/Recreations

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/selenium-coop-application.git
    cd selenium-coop-application
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Create a `.env` file in the project root and set the following variables:

    ```env
    MY_USERNAME = "your_username"
    MY_PASSWORD = "your_password"
    ```

## Usage

Run the script by executing:

```bash
python script_name.py

# Functional Testing Case

This project to automate web testing ,screen recording , screenshot as part of our software testing process.

## Contents

- Project Description
- Basic Structure
  - Functionalities
  - Screenshots of the Implementation
- Tech Stack
- How to Run
  

## Project Description

In this project, i developed a Python script that automates interactions with a web application and records the screen during execution. The script uses Selenium for web automation and OpenCV for screen recording. This approach allows us to test web application functionality and capture the entire process for review and debugging.

## Basic Structure

### Functionalities

- **Screen Recording:**
  - Records the screen while the test is running and saves the recording as a video file (`test_recording.mp4`).

- **Web Automation:**
  - Initializes a Selenium WebDriver for Chrome.
  - Navigates to a specified URL and performs login using predefined credentials.
  - Automates navigation to a file upload section and uploads a file.
  - Validates the upload and captures a screenshot of the final state of the web application.

- **Error Handling:**
  - Logs errors and information throughout the script to facilitate debugging and monitoring.

#### Final Output Screenshot

<kbd><img src="C:/Users/HP/Desktop/Automate_Testing/Final_Output.png" width="800px" alt="Final Output Screenshot"></kbd>

## Tech Stack

- **Testing Tools:** Selenium, OpenCV

## How to Run

1. **Install Dependencies:**
   - Ensure you have Python installed.
   - Install the necessary Python packages using `pip`:

     ```bash
     pip install -r requirements.txt
     ```

3. **Update Configuration:**
   - Ensure that the file paths in the script (`demo-data.xlsx`, `final_output.png`) are correct and adjust if necessary.

4. **Run the Script:**
   - Execute the Python script using:

     ```bash
     python script_name.py
     ```

   - The script will start recording the screen, run the web automation test, and save the results.

5. **Check Results:**
   - The screen recording will be saved as `test_recording.mp4`.
   - The final output screenshot will be saved as `final_output.png` in the `Automate_Testing` folder.




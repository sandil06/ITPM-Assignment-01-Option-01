# IT23849006 - IT3040 Assignment 1

## ProjectTitle
Automated Testing for Singlish to Sinhala Transliteration System

## Repository
https://github.com/sandil06/ITPM-Assignment-01-Option-01

## Project Structure

It3040_Assinment_1

-- test_automation.py              -> Playwright automation script
-- Assignment 1 - Test cases.xlsx  -> Excel file test cases & results
-- IT23849006_requirements.txt     -> Python dependencies
-- IT23849006_README.md            -> Project documentation
-- venv/ (optional)                -> Virtual environment (not required)

---

## Technologies used

- Python
- Playwright (UI Automation)
- OpenPyxl (Excel handling)

## How to run the project

1. open terminal inside project folder

2. (Optional) Activate virtual environment
venv\Scripts\activate

3. Install dependencies
   pip install -r requirements.txt
   playwright install

4. Run the automation script
   python test_automation.py --excel "IT - test cases.xlsx"  --url "https://www.pixelssuite.com/chat-translator"

---

## Output

- Results are automatically written to the Excel file
- Colums updated :
    - Actual output
    - Status (PASS / FAIL)

---

## Test Case Details

- Total Test Cases: 50
- Test Type: Negative Testing

##  Covered Scenarios

- Mixed language inputs (Singlish + English)
- Spelling variations
- Emojis & symbols 
- Real-world scenarios (banking, travel, apps)
- System-related messages (errors, logs)
- Numeric and date inputs (e.g., 2025-05-04, 10:30 PM)

---

##  Important Notes

- This system uses strict comparison
- Even small differences in Sinhala output (spacing, formatting, spelling) will result in FAIL
- Some failures are expected due to:
  - Transliteration inconsistencies
  - Mixed language complexity
  - UI timing delays

---

##  Student Information

- Student ID: IT23849006
- Module: IT3040
- Assignment: Assignment 1 (Option 1)

---

##  Final Status

✔ Automation script working  
✔ Excel-based validation completed  
✔ Test coverage includes multiple edge cases  

---

## Submission Notes
 
- Virtual environment (venv) is excluded from submission
- All required files are included
- Project is fully runnable using `IT23849006_requirements.txt`

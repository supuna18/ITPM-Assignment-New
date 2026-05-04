# ITPM Assignment 1 - Option 1 (Transliteration Accuracy Testing)

**Student Registration Number:** [Insert Your Registration Number Here]

---

## Project Description

This assignment focuses on evaluating the transliteration accuracy of the **"Chat Sinhala"** function available on the PixelsSuite Chat Translator platform.

The objective of this project is to identify and analyze 50 negative test cases related to informal Singlish typing patterns. The testing process is automated using the Playwright framework to evaluate how accurately the system handles different user input variations such as greetings, questions, slang, shortened spellings, English word insertions, and casual chat-style Sinhala typing.

The project also aims to identify weaknesses, inconsistencies, and potential transliteration failures within the system.

---

## Technologies Used

- Python 3.11 / 3.12
- Playwright Framework
- Openpyxl Library
- Microsoft Excel

---

## Prerequisites

Before running the project, ensure the following are installed on your system:

- Python 3.11 or Python 3.12
- Google Chrome or Chromium Browser
- Internet Connection

---

## Installation and Setup

### 1. Clone or Download the Repository

Download the project files or clone the repository to your local machine.

```bash
git clone <repository-url>
```

---

### 2. Install Required Dependencies

Run the following command to install the required Python packages:

```bash
pip install playwright openpyxl
```

---

### 3. Install Playwright Browser Binaries

Execute the following command:

```bash
playwright install
```

---

## Automated Testing Execution

To execute the automated testing process and store the generated results inside the Excel file, run the following command:

```bash
python test_automation.py --excel "Test cases.xlsx" --sheet "Sheet1" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 10000 --type-delay-ms 100 --save-every 1
```

---

## Project File Structure

```plaintext
├── test_automation.py
├── Test cases.xlsx
├── README.md
```

### File Descriptions

- **test_automation.py**  
  Main automation script responsible for browser interactions, input execution, and result collection.

- **Test cases.xlsx**  
  Excel file containing all 50 negative test cases, expected outputs, actual outputs, and testing observations.

- **README.md**  
  Project documentation and execution instructions.

---

## Scope of Testing

This project specifically evaluates the **"Chat Sinhala"** transliteration mode available in the PixelsSuite Chat Translator.

The testing scope includes multiple categories of informal Singlish typing patterns such as:

- Shortened spellings
- Missing vowels
- English word insertions
- Mixed Sinhala-English phrases
- Numeric suffix usage
- Slang expressions
- Informal chat language
- Casual conversational inputs
- Abbreviated typing styles

---

## Testing Objectives

The primary objectives of this testing process are:

- Identify transliteration inaccuracies
- Detect system weaknesses
- Analyze handling of informal Sinhala typing
- Evaluate consistency of transliteration outputs
- Examine limitations in mixed-language inputs
- Document failure scenarios and edge cases

---

## Expected Outcome

By completing this assignment, the project aims to provide a detailed analysis of the transliteration accuracy of the PixelsSuite Chat Translator and identify areas that require improvement for better handling of real-world informal Singlish communication.

---

## Reference Website

PixelsSuite Chat Translator:  
https://www.pixelssuite.com/chat-translator

# Python Utility Projects

This repository contains a collection of small utility projects built with Python, including an Alarm, Calculator, Morse Code Detection, and QR Code Generator.  Each project is designed to demonstrate practical applications of Python programming and can be used as standalone tools or as learning resources.

## Table of Contents

* [Projects](#projects)
* [Installation](#installation)
* [Usage](#usage)
* [Requirements](#requirements)

## Projects

### Alarm

A simple alarm clock that triggers a sound or notification at a user-specified time. 

* **Features**: Set time, sound alert, customizable duration.
* **File**: `alarm.py`

### Calculator

A basic command-line calculator supporting addition, subtraction, multiplication, and division.

* **Features**: Simple arithmetic operations, user-friendly input. 
* **File**: `calculator.py`

### Morse Code Detection

A tool to encode text into Morse code and decode Morse code back into text. 

* **Features**: Text-to-Morse and Morse-to-text conversion, basic error handling. 
* **File**: `morse.py`

### QR Code Generator

Generate QR codes from text or URLs and save them as image files.

* **Features**: Customizable QR code size, save as PNG. 
* **File**: `qr.py`

## Installation

1.  Clone the repository:

    ```bash
    git clone [https://github.com/MANJU-AR/python-utility-projects.git](https://github.com/MANJU-AR/python-utility-projects.git)
    cd python-utility-projects
    ```
2.  Install dependencies: Ensure you have Python 3.x installed. 

    Then, install the required libraries:

    ```bash
    pip install -r requirements.txt
    ```
3.  Run a specific project: Navigate to the project folder and execute the desired script.

## Requirements

The following Python libraries are required:

* `tkinter`, `datetime`, `time`, `winsound`, `threading` (for Alarm)
* `qrcode` (for QR Code Generator) 
* `tkinter`, `functools`, `partial` (for Calculator) 
* No additional libraries are required for the Morse Code Detection project beyond the Python standard library.

## Usage

### Alarm

Set an alarm for a specific time:
```bash
python alarm.py
```
- Enter the time in `HH:MM` format (24-hour clock).
- The alarm will play a sound when the time is reached.

### Calculator
Perform basic arithmetic:

```bash
python calculator.py
```
- Follow the prompts to enter numbers and choose an operation (+, -, *, /).

### Morse Code Detection
Convert text to Morse code:
```bash
  python morse.py
```
- Enter your input accordingly and get Morse code for the input.

### QR Code Generator
Create a QR code from text or a URL:
```bash
  python qr.py
```
- Enter the text or URL you want to encode.
- The QR code will be saved as qrcode.png in the project directory.

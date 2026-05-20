# Lab aw Calibration Engine

## Overview
The Lab aw Calibration Engine is a lightweight and interactive web-based calibration tool designed for correcting raw water activity (aw) measurements obtained from laboratory instruments. The application uses linear regression models to convert experimental readings into accurate calibrated aw values in real time.

This tool simplifies laboratory calibration workflows by allowing users to select an instrument, enter raw experimental readings, and instantly obtain corrected calibration values based on predefined standard datasets.

The application is fully built using HTML, CSS, and JavaScript, making it fast, responsive, and easy to run directly in any web browser without requiring backend setup.

------------------------------------------------------------

## Features
- Real-time water activity calibration
- Multiple instrument support
- Linear regression-based correction engine
- Instant calibrated aw output
- Dynamic equation display
- Responsive modern UI
- Lightweight standalone application

------------------------------------------------------------

## Technologies Used
- HTML5
- CSS3
- JavaScript

------------------------------------------------------------

## How It Works
The system uses predefined:
- Standard aw values
- Experimental readings

Using these datasets, the application calculates a linear regression equation:

y = mx + c

Where:
- x = raw experimental reading
- y = calibrated aw value
- m = slope
- c = intercept

Whenever the user changes:
- Instrument selection
- Raw input value

the calibrated aw value updates automatically in real time.

------------------------------------------------------------

## Supported Instruments
- Labmaster neo
- Meter 2
- Meter 3

Additional instruments can easily be added by updating the calibration arrays in the configuration section.

------------------------------------------------------------

## Project Structure

├── index.html
├── styles.css
├── script.js
└── README.md

------------------------------------------------------------

## Calibration Workflow
1. Select laboratory instrument
2. Enter raw experimental reading
3. System calculates regression equation
4. True calibrated aw value is displayed instantly

------------------------------------------------------------

## User Interface Highlights
- Clean laboratory dashboard
- Interactive real-time calculations
- Mobile and desktop responsive design
- Dynamic equation visualization

------------------------------------------------------------

## Future Improvements
- CSV data upload support
- Calibration graph visualization
- Export calibration reports
- Database integration
- Advanced regression fitting methods

------------------------------------------------------------

## Run the Project
Simply open:

index.html

in any modern web browser.

No installation or server setup required.

------------------------------------------------------------

## Conclusion
The Lab aw Calibration Engine provides a simple and efficient solution for performing laboratory water activity calibration using regression-based correction models. By combining scientific calibration logic with a clean interactive interface, the tool improves calibration accuracy, usability, and workflow efficiency.

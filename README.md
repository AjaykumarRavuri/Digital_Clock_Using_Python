## Digital Clock Using Python
This is a simple digital clock application built using Python and Tkinter. The clock displays the current time in hours, minutes, and seconds, and updates every 200 milliseconds.

## Features
Displays current time in HH:MM
format.
The clock updates automatically every 200 milliseconds.
User-friendly interface with a clear and bold font.
### Requirements
Python 3.x
Tkinter library (usually included by default in Python installations)
### How to Run
Clone the repository:
bash
git clone https://github.com/veerendranadhkoppula/Digital_Clock_Using_Python.git
## Navigate to the project directory:
bash
cd Digital_Clock_Using_Python
## Run the script:
bash
python Digital_Clock.py
## Code Explanation
The script uses the time module to get the current time in the desired format.
The Tkinter library is used for creating the GUI, where:
A Label widget is used to display the current time.
The after method is used to continuously update the time displayed by the clock.

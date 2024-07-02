# LGMVIP-Web-Task-2
LGMVIP-Web-Task-2
Hello folks,

I am here with my new application, "Calculator," which is made using HTML, CSS, and JavaScript. Now, I am going to discuss the technicalities, features, and some future changes that can be done to make it a better calculator.

Features:

This calculator can perform multiple calculations.
It can handle addition, subtraction, multiplication, and division operations.
The calculator supports calculations involving floating-point numbers, both integers and non-integers.
A "DustBin" emoji is provided to clear all the values currently displayed on the panel.
In case a user mistakenly taps a button, the backspace emoji is used to clear the last pressed value.
A "00" (Double Zero) button is provided along with the "0" button to allow faster input of numbers with extra zeros.
The user interface is designed to be simple, with a light-colored, minimalistic layout for ease of use.
Technicalities:

The page structure is created using HTML, and CSS is used for styling the calculator.
Instead of using a separate JavaScript file, the JavaScript code is included within the HTML page.
Rather than creating individual functions for each calculation, the calculator extracts values from the input box and performs calculations using a single function.
The eval() function is used in the HTML file to evaluate the mathematical statements entered in the input box. (Learn more about the eval() function: https://www.w3schools.com/jsref/jsref_eval.asp)
Tapping the "All Clear" button replaces the input box's values with an empty string (""), effectively clearing the calculator.
For the backspace feature, the input box values are converted into a string, and then the last character is removed using the slice(0,-1) method.
Div tags within the form tag are used to organize the rows.
Future Changes:

Currently, the calculator does not allow entering values and operators from the keyboard. To improve usability, keyboard input functionality should be implemented.
To handle larger outputs, the calculator should be modified to automatically adjust the output size to fit the screen properly.
More complex functions and expressions could be added to enable the calculator to handle more advanced calculations.
Enhancing the calculator's appearance by incorporating various transitions and styles will make it more visually appealing.

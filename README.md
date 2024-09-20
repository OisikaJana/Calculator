# Calculator

1. HTML Document Structure
The <!DOCTYPE html> declaration indicates that this is an HTML5 document.

<head> Section:
Meta tags: These define the document's character encoding (UTF-8), compatibility with Internet Explorer (X-UA-Compatible), and responsive layout (viewport meta tag).
Title: Sets the title of the document, which appears in the browser tab.
Stylesheet link: It links to an external CSS file (calc.css) where the styles for the calculator will be defined.
<body> Section:
The body contains the actual content of the calculator:

Container (div.container): This is the main wrapper for the calculator.
Display (input.display): This is the input field where the result and input values are displayed.
Buttons (div.buttons): This section contains all the buttons for the calculator, including numbers, operators, and functions. Each button is implemented using the <button> element.


2. Buttons
Each button is labeled with its function or value. Buttons can be divided into two categories:

Operator Buttons:
These buttons include operators such as +, -, *, /, %, log, AC (clear), DEL (delete), and the equals sign (=) for calculation. Some of these buttons also have special attributes like data-value, which is useful for JavaScript to identify the operation.
The button for π allows the user to use the Pi constant in calculations.
Number Buttons:
These buttons represent digits (0-9) and decimal point (.). Each number button has a data-value attribute to represent its value.
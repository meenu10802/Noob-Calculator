# Noob-Calculator
This is a simple project implemented to demonstrate the things I learned in JavaScript during my 5-month web development journey.

readonly Attribute:
The readonly attribute on an <input> element prevents users from directly typing or pasting values into the input field. It's primarily used for displaying information, such as the result of a calculation, without allowing user modification.
 
Calling Functions in JavaScript:
Mechanism: When a button is clicked in an HTML document, you can trigger a JavaScript function to execute specific actions. This is achieved by attaching an event listener (e.g., onclick) to the button element. The event listener calls the desired JavaScript function, optionally passing arguments (values or data) to the function for processing.

Default Flexbox Behavior: By default, the body element often has display: flex applied, which arranges child elements horizontally (flex-direction: row).
Overriding Default Behavior: To position the calculator below the h1 element, you can override the default flex behavior by setting flex-direction: column on the body or by using CSS to position the h1 element absolutely or relatively.

Function:
number(x)
Appends the digit or decimal point (.) to the display field.

operator(x)
Appends the selected operator to the display field.

calculate()
Evaluates the arithmetic expression entered in the display field using the eval function. Displays an error message if the input is invalid.

Event Listeners:
Clear Button (C): Clears the entire input field.
Delete Button (CLR): Deletes the last character from the input field.


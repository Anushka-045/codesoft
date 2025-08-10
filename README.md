Description
This is a basic web-based calculator implemented using HTML, CSS, and JavaScript. It allows users to perform simple arithmetic operations including addition, subtraction, multiplication, and division. The calculator has a clean and modern blue-themed interface with responsive button layout and displays the ongoing input and results dynamically.

Features
Simple Arithmetic Operations: Supports addition (+), subtraction (-), multiplication (*), and division (/).

Dynamic Display: Shows the current input expression and updates the display with the result upon calculation.

Clear Function: A dedicated “C” button to reset the input and display.

Input Validation: Prevents multiple consecutive operators to avoid invalid expressions.

Error Handling: Displays “Error” if the expression is invalid or results in an error during evaluation.

Responsive Button Grid: Uses CSS Grid to layout calculator buttons evenly in a 4-column format.

User Experience Enhancements:

Cursor changes to pointer on buttons.

Button hover effect changes color for interactive feedback.

Large buttons and clear font for easy readability.

Result Handling: After showing the result, entering a new number clears the previous result, allowing smooth chaining of calculations.

Unique Aspects
CSS Grid Layout: Instead of traditional flexbox or inline blocks, the button layout uses CSS Grid for precise and clean alignment.

Operator Replacement: If the user presses an operator consecutively, the last operator is replaced with the new one instead of appending — avoiding invalid expressions.

Simple but Effective Error Handling: Uses a try-catch block around eval() to catch any exceptions gracefully.

Visual Styling: The blue color scheme with subtle box shadows and rounded corners provides a polished, modern UI look.

Minimalistic & Self-contained: The entire calculator functionality is implemented in a single HTML file with embedded CSS and JS, making it portable and easy to deploy.

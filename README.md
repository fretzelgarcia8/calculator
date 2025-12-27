
Calculator
A beautiful, responsive, and functional web-based calculator featuring a "cute" glassmorphism aesthetic. This project utilizes a soft pink and cream color palette, backdrop-filter effects, and a custom "preview" display logic to track operations in real-time.

✨ Features
Glassmorphism UI: High-quality design using backdrop-filter for a blurred-glass effect and soft shadows.

Dual Display:

Preview Display: Shows the full ongoing expression or the last calculated result.

Main Display: Focuses on the current number being typed or the final answer.

Keyboard Support: Full integration with physical keyboards (numbers, operators, Enter, Escape, and Backspace).

Smart Logic:

Prevents multiple decimal points in a single number.

Allows leading negative numbers.

Operator swapping (e.g., typing + then - automatically replaces the operator).

Percentage Handling: Pre-processes percentage patterns for logical calculations.

Responsive Design: Optimized for mobile, tablet, and desktop screens using CSS clamp() and media queries.

🚀 Getting Started
Prerequisites
You only need a modern web browser (Chrome, Firefox, Safari, or Edge) to run this project.

Installation
Clone the repository:

Bash
git clone https://github.com/fretzelgarcia8/calculator.git
Navigate to the folder:

Bash
cd calculator
Open the project: Simply double-click index.html to open it in your default browser.

🛠️ Built With
HTML5: Semantic structure and ARIA labels for accessibility.

CSS3: Custom properties (variables), Flexbox, CSS Grid, and Glassmorphism effects.

JavaScript (ES6+): Functional logic, keyboard event listeners, and dynamic DOM updates.

📂 File Structure
index.html: The core structure and button layout.

style.css: All styling, including the custom "cute" color palette and responsive breakpoints.

script.js: The calculation engine and event handling.

⌨️ Keyboard Shortcuts
Key	Action
0-9	Enter numbers
.	Decimal point
**+, -, , /*	Operators
%	Percentage
Enter / =	Calculate result
Backspace	Delete last character
Escape	Clear all (AC)
📝 License
This project is not licensed and is provided for educational purposes only.


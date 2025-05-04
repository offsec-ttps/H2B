---
description: Set monthly/annual budgets and compare against actual expenses.
---

# Budget Planner

## AI Prompt for Budget Tracker

```
Please generate the complete HTML, CSS, and JavaScript code for a dynamic, single-page web application that functions as a personal monthly budget tracker. The application should have the following features:

Core Structure (HTML):
A main container for the application.
An input field at the top for the user to enter their 'Total Monthly Salary'. This input should only accept numbers.
A section to display the budget visualization (the donut chart).
A button (ideally styled as a '+' icon) to trigger adding a new expense.
A simple list or table area below the chart (optional, but good for clarity) to display the added expense categories and their amounts.
Styling (CSS):
Create a visually appealing and clean layout. Use modern CSS techniques (like Flexbox or Grid) for layout.
Style the donut chart container.
Style the text displayed in the center of the donut chart (make it prominent).
Style the '+' button.
Style the expense input form/modal (if using one).
Ensure the remaining balance display clearly indicates if the value is negative (e.g., using red color).
Make the page reasonably responsive for different screen sizes.
Visualization (JavaScript & HTML/CSS or Library):
Implement a donut chart. You can use a JavaScript charting library like Chart.js (preferred for ease of dynamic updates) or create a custom one using SVG/Canvas and CSS.
Initial State: When the page loads (or after the salary is entered), the donut chart should display a single segment representing the entire entered salary as 'Available Balance'.
Center Display: The center of the donut chart must initially display the 'Total Monthly Salary' entered by the user. As expenses are added, this central display must update dynamically to show the 'Remaining Balance' (Total Salary - Total Expenses).
Functionality (JavaScript):
Salary Input: When the user enters their salary and potentially clicks a 'Set Salary' button or blurs the input field, store this value and update the initial donut chart and center text.
Add Expense:
Clicking the '+' button should prompt the user to enter two mandatory fields:
Category: Name of the expense category (e.g., "Groceries", "Rent", "Utilities").
Expenditure: The amount spent (numeric).
A simple modal popup or inline form can be used for this input. Include basic validation (Category cannot be empty, Expenditure must be a positive number).
Dynamic Updates: Upon successfully adding a new expense:
Store the expense data (e.g., in a JavaScript array of objects: [{ category: 'Rent', amount: 1000 }, { category: 'Food', amount: 300 }]).
Recalculate: Sum up all expenditures. Calculate the Remaining Balance = Total Salary - Total Expenditures.
Update Donut Chart:
Add a new segment to the donut chart representing the newly added expense category and its amount. Assign a distinct color to the new segment.
The original 'Available Balance' segment should shrink accordingly. If expenses exceed salary, the chart might show only expense segments.
Update Center Display: Update the text in the center of the donut chart to show the current Remaining Balance.
Negative Balance: If the Remaining Balance is negative, display it as such (e.g., "-$50.00") and potentially change the text color to red.
Update Expense List (Optional): If you included an expense list area, add the new category and amount to it.
Investment Planning Aspect:
The 'Remaining Balance' displayed inherently represents the funds available for savings or future investments after accounting for all entered expenses. No separate section is needed unless specified, but the logic should be clear.
Code Structure:
Provide the code within a single HTML file using <style> and <script> tags, or provide separate index.html, style.css, and script.js files.
Ensure the JavaScript code is well-commented, explaining the logic for data storage, calculations, and DOM manipulation/chart updates.
Use modern JavaScript (ES6+). Please generate the code that fulfills all these requirements."
```

## dev.tool prompt

```
Based on your requirements, I'll create a beautifully designed monthly budget tracker with a donut chart visualization. The application will help users track their expenses against their monthly salary with an intuitive, dynamic interface.

Core Features:

Salary input with real-time validation
Dynamic donut chart visualization of budget allocation
Add expense functionality with category and amount
Remaining balance calculation and display
Expense list with categorized spending
Color-coded visualization for different expense categories
Negative balance warning with visual indicators
Responsive design for all device sizes
Design Elements:

Clean, minimalist interface with intentional white space and clear hierarchy
Color system with primary blue (#3B82F6), accent green (#10B981), warning orange (#F59E0B), and danger red (#EF4444)
Smooth animations for chart transitions and expense additions
Card-based layout with subtle shadows and rounded corners
Consistent 8px spacing system throughout the interface
Modern typography with appropriate contrast ratios for readability
Interactive elements with hover and focus states for better usability
Responsive breakpoints for mobile, tablet, and desktop views
```

<figure><img src="../../.gitbook/assets/cccc.png" alt=""><figcaption></figcaption></figure>

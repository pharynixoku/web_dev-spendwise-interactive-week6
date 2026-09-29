# SpendWise Interactive

## Project Description

SpendWise is a personal budgeting dashboard that helps users manage their monthly budget and expenses.

This week's project improves the previous SpendWise dashboard by adding JavaScript interactivity. Users can set a budget, add multiple expenses, view their total expenses, and see their remaining balance.

The application also provides feedback depending on the user's spending situation.

## Project Files

- `index.html` - Contains the structure of the SpendWise dashboard.
- `style.css` - Contains the design, layout, responsive styling, and dark theme.
- `script.js` - Contains the JavaScript functionality.
- `README.md` - Contains information about the project.

## Improvements Made This Week

The SpendWise project was improved by adding:

- Interactive budget input.
- Interactive expense input.
- Expense arrays.
- Loops for processing expenses.
- Conditional statements.
- Dynamic dashboard updates.
- Event listeners.
- Budget status messages.
- Clear all expenses functionality.

## Conditional Statements

Conditional statements are used to evaluate the user's financial situation.

For example, the application checks whether the user has exceeded the budget:

```javascript
if (remainingBalance < 0) {
    budgetMessage.textContent =
        "You have exceeded your budget.";
}
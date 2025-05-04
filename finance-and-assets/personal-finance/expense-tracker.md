---
description: Categorized spending logs with trend visualizations.
---

# Expense Tracker

## dev.tool prompt

```
Build a separate React-based page for "Expense Tracker" module for a personal life management platform called "Human 2nd Brain".

Key Requirements:

Category Management:

Integrate the following top-level expense categories:
Housing & Utilities
Transportation
Food & Groceries
Personal Care & Lifestyle
Healthcare & Medical
Family & Children
Domestic Help & Services
Loans, EMIs & Debt
Insurance
Entertainment & Subscriptions
Travel & Events
Festivals, Gifting & Charity
Rural / Agricultural Expenses (optional)
Miscellaneous / Custom Expenses
Each top-level category must support predefined subcategories (refer to full lists from user input).
Allow users to customize, add, edit, or remove subcategories.
Data Input & Management:

Create a responsive UI for adding new expense entries with:
Date
Amount
Category & Subcategory (dropdown)
Payment Mode (e.g., Cash, UPI, Card, Wallet)
Optional Tags and Notes
Enable filtering by date range, category, subcategory, and amount.
Support inline editing and deletion of records.
Save all data using a local state or mock backend (e.g., JSON Server or LocalStorage for MVP).
Dashboard & Visualization:

Provide a dashboard view with:
Total Expenses This Month
Category-wise Expense Breakdown (Pie/Donut Chart)
Monthly Trend (Bar or Line Chart)
Budget vs Expense comparison with color indicators
Make charts interactive using Recharts or Chart.js.
User Experience Features:

Search bar for expense descriptions/tags
Option to export expenses as CSV/PDF
Budget setting per category with warning indicators
Responsive layout (mobile + web)
Light and dark theme support
Toast notifications on add/edit/delete
Component Architecture:

Use modular components: ExpenseForm, ExpenseList, CategorySidebar, DashboardOverview, ChartsPanel
Implement a sidebar navigation menu with collapsible accordion for categories and subcategories
Bonus Features (Optional):

Add recurring expense scheduling (e.g., monthly rent)
Smart alerts for overspending
Integration-ready hooks for syncing with bank SMS APIs or UPI
Use TailwindCSS for styling. Structure code cleanly using React best practices with reusable hooks and context for global state management.

Make the design intuitive, minimal, and human-centered, suitable for a daily life management app.
```

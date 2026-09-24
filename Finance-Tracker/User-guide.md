# Finance Tracker — User Guide

## 1. Introduction

Finance Tracker is a private, local-first personal finance workspace. It helps you record income and expenses, set monthly budgets, manage bills, track savings goals, and understand your cash flow.

Your financial data stays in your browser on the current device. The app does not require an account or upload your data to a server.

## 2. Getting Started

1. Open `index.html` in a modern browser.
2. Open **Preferences** from the top-right data menu.
3. Enter your name and select your currency.
4. Go to **Financial Planner → Setup**.
5. Add your income sources, budgets, savings goals, and regular bills.
6. Use **Transactions** whenever money comes in or goes out.

## 3. Navigation

The sidebar contains:

- **Dashboard** — a finance-only summary of your current position.
- **Financial Planner**
  - **Overview** — monthly financial summary and quick actions.
  - **Setup** — income sources, budgets, savings goals, and bills.
  - **Transactions** — add, edit, filter, and remove transactions.
  - **Calculator** — six independent financial calculators.

On a small screen, use the menu button to open or close the sidebar.

## 4. Dashboard

The Dashboard automatically uses your saved finance data. It shows:

- income received this month;
- spending this month;
- money left to spend;
- savings rate;
- expected income;
- budgeted amount;
- pending bills;
- six-month cash-flow chart;
- spending by category;
- recent transactions;
- budget usage.

Select **Open Financial Planner** to move from the summary into the detailed workspace.

## 5. Financial Overview

Use the left and right arrows beside the month to review another month. Return to the current month when needed.

### Main balance

**Left to spend** is calculated as:

`Income received − Expenses recorded`

The page also shows income, total spending, savings rate, and the percentage of income already used.

### Quick actions

- **Add income** records money received.
- **Add expense** records money spent.
- **Mark received** records a due income source as received.
- **Mark paid** records a bill as an expense.

### Other overview sections

- **Money in** compares received and expected income.
- **Money out** groups expenses by category.
- **Budgets** compares actual category spending with each monthly limit.
- **Bills** shows bills due during the selected month.
- **Savings goals** shows progress toward each target.
- **Month review** summarizes the selected month.
- **Income vs spending** can be viewed by month or year.

## 6. Setup

### Income sources

Add a regular income source with:

- source name;
- monthly amount;
- day it normally arrives.

The source appears as expected income each month. Use **Mark received** when the payment arrives. A source can be paused, resumed, edited, or removed. Removing a source does not have to remove its past transaction history.

### Budgets

Choose an expense category and enter its monthly limit. The same limit is reused every month until changed.

Budget usage is calculated from expense transactions in that category. You can also create and manage categories. A category currently used by saved data cannot be removed until those references are changed.

### Savings goals

Enter a goal name, target amount, and optional monthly plan. Use **Add deposit** to record progress. A deposit is recorded as an expense linked to that goal, so totals remain connected.

### Bills

Enter:

- bill name;
- amount;
- due day from 1 to 31;
- expense category.

Bills appear in the monthly overview. Select **Mark paid** to create the related expense transaction. Bills can be paused, resumed, edited, or removed.

## 7. Transactions

### Add a transaction

1. Select **Income** or **Expense**.
2. Enter the amount.
3. Choose a category.
4. Select the date.
5. Add an optional note.
6. For income, optionally connect it to an income source.
7. Save the transaction.

You can create a new category while adding a transaction.

### Review and manage transactions

The selected month shows total income, spending, and net balance. Use the type and category filters to narrow the history.

Each transaction can be edited or removed. After removal, use **Undo** immediately if the item was deleted by mistake.

## 8. Financial Calculators

Calculator results are estimates and do not change your saved transactions.

### Loan & EMI

Enter the principal, annual interest rate, and term in years to estimate the monthly payment and total interest.

### Savings growth

Enter a starting balance, monthly deposit, expected annual return, and number of years to estimate the future value.

### Savings goal

Enter a target, amount already saved, and remaining months to calculate the monthly amount required.

### Quick percentage

Enter a base amount and percentage, then calculate the percentage value, add it, or subtract it.

### Debt payoff

Enter the outstanding balance, annual interest rate, and monthly payment to estimate payoff time and total interest. If the payment does not cover the interest, the app warns that the payment is too low.

### Business profit

Enter revenue, fixed costs, and variable costs to calculate total costs, net profit, profit margin, and break-even revenue.

## 9. How the Calculations Stay Connected

The Dashboard and Overview are calculated automatically from the same records:

- income transactions increase received income;
- expense transactions increase spending;
- budget usage comes from expenses in each category;
- marking a bill paid creates an expense;
- marking income received creates an income transaction;
- savings deposits update the goal and create a linked expense;
- changing the selected month refreshes all monthly totals and charts.

To keep reports accurate, always record real money movement as a transaction.

## 10. Preferences, Backup, and Restore

Open the top-right data menu to access these tools.

### Preferences

Set your display name and preferred currency. Changing the currency changes the displayed currency label; it does not convert old amounts using exchange rates.

### Export backup

Select **Export backup** to download a JSON backup containing your finance data. Keep it in a safe place and create a new backup regularly.

### Import backup

1. Select **Import backup**.
2. Choose a backup created by Finance Tracker.
3. Confirm the import.
4. Review the Dashboard and Transactions after restoration.

Importing a backup replaces the current finance data in the browser. Export the current data first if it may still be needed.

## 11. Recommended Monthly Workflow

1. Check expected income and upcoming bills.
2. Mark income received when it arrives.
3. Record every expense in the correct category.
4. Review budget usage during the month.
5. Mark bills paid only after payment.
6. Add savings deposits when money is moved toward a goal.
7. Review the charts and month summary.
8. Export a backup at the end of the month.

## 12. Troubleshooting

- **Totals look incorrect:** check the selected month, transaction type, amount, and date.
- **A bill is not counted:** mark it paid or add the related expense manually.
- **Income is only expected:** use **Mark received** when it actually arrives.
- **Budget usage is wrong:** verify that expenses use the correct category.
- **Data is missing in another browser/device:** data is stored locally; export a backup on the original device and import it on the new one.
- **Data disappeared after browser cleanup:** restore the latest exported backup.

## 13. Privacy Note

All data is stored locally in the browser. Anyone with access to the same browser profile may be able to open it, so use a secured device and keep backup files protected.

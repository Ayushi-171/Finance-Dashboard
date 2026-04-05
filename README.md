# Finsight — Finance Dashboard

🔗 **Live Demo:** [View Dashboard]()

A clean and interactive finance dashboard built with HTML, CSS, and vanilla JavaScript.

Built as a screening assignment for the Frontend Developer Intern role at Zorvyn FinTech.

---

## How To Run

No installation needed.

1. Download or clone this repository
2. Open `zorvyn_finance_dashboard.html` in any browser
3. That's it!

---

## Features

### Dashboard Overview
- Summary cards showing Total Balance, Income, Expenses and Savings Rate
- Balance trend line chart (income vs expense over time)
- Spending breakdown donut chart by category
- Monthly cashflow bar chart

### Transactions
- Full transaction table with date, amount, category and type
- Filter by type — income or expense
- Filter by category
- Sort by date or amount
- Search by description or category
- Date range filter — pick any From and To date
- Add, edit and delete transactions (Admin only)

### Insights
- Top spending category with progress bar
- Savings rate indicator
- Average monthly spend
- Monthly income vs expense comparison chart
- Category breakdown horizontal bar chart

### Role Based UI
- Switch between Admin and Viewer using the dropdown in the sidebar
- Admin can add, edit and delete transactions
- Viewer has read only access — no add or edit buttons shown

### Other
- Mock API simulation with shimmer skeleton loading states
- Smooth fade transitions between views
- Fully responsive — works on mobile and desktop
- Time period filter — Last 3, 6 or 12 months

---

## Tech Stack

- HTML5
- CSS3 — Flexbox, Grid, CSS Variables, Animations
- Vanilla JavaScript — Array methods, DOM manipulation, Async/Await
- Chart.js — for all data visualizations
- Google Fonts — DM Sans + DM Mono

---

## Project Structure

Finance-Dashboard/
├── zorvyn_finance_dashboard.html   ← entire app (HTML + CSS + JS in one file)
└── README.md                       ← project documentation

### Inside the HTML file:
- `<style>`  → all styling (CSS variables, layout, animations, responsive rules)
- `<body>`   → all structure (sidebar, topbar, views, modal)
- `<script>` → all logic (mock API, state management, filtering, charts)

## Design Decisions

- Single file approach — the assignment allowed plain JavaScript and keeping everything
  in one file makes it simple to run with zero setup
- Dark theme — chosen for a finance context where users spend long periods
  reviewing data
- Mock data — 26 transactions across 6 months covering realistic Indian
  expense categories
- Role based UI is simulated on the frontend using a state variable and
  conditional rendering — no backend required as per assignment instructions

---

## Author

Ayushi
Frontend Developer Intern Applicant — Zorvyn FinTech

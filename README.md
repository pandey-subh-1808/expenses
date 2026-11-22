# Daily Expense Calendar & Tracker

A lightweight, single-file web application for logging daily expenses, setting daily spending limits, and tracking total spending on an interactive monthly calendar.

## Features

- **Interactive Monthly Calendar:** View daily spending totals directly inside each calendar date with automatic color indicators (under budget, nearing limit, or over limit).
- **Daily Expense Limit:** Set a custom daily spending target and see your remaining or exceeded budget for any selected date.
- **Total Spent Till Now Dashboard:** Real-time summary cards tracking:
  - All-time total spent and total logged entries
  - Current viewing month's total spending
  - Selected date total and budget status
  - Daily average across active spending days
- **Category & Item Logging:** Add or delete itemized expenses per date across categories (`Food & Dining`, `Travel & Commute`, `Bills & Recharge`, `Shopping`, `Study & Books`, and `Other`).
- **Offline Persistence & Export:** Automatically saves data in the browser via `localStorage` and includes one-click JSON backup export.

## Getting Started

### Run Locally
1. Download or clone this repository.
2. Open `index.html` in any modern web browser (Chrome, Edge, Firefox, Safari).

### Host with GitHub Pages
1. Push `index.html` to the `main` branch of your GitHub repository.
2. Open **Settings → Pages** in your repository.
3. Under **Build and deployment**, select **Deploy from a branch**, choose `main` (`/root`), and click **Save**.

## Project Structure

```text
├── index.html   # Complete HTML, CSS, and JavaScript application
└── README.md    # Project documentation

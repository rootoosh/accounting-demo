# Local Accounting System (demo)

A single-file, Hebrew (RTL) bookkeeping web app. It runs entirely in the browser: there is no server, no sign-in and nothing is uploaded anywhere.

## Features

- Accounts, deposits, withdrawals and a commission table, with account balances
- Automatic commission handling: a deposit with a commission code creates a fee withdrawal and a matching deposit to the association account
- Import of accounts, commissions, deposits and withdrawals from Excel/CSV files
- Reports (accounts, summary, account movements) with Excel export and printing / PDF
- Several independent systems, each in its own browser tab
- Adjustable column widths and color-coded amounts (green for credit, red for debit)

## How your data is stored

- **Excel file mode** (Chrome or Edge): every change is saved to an Excel file that you choose on your own computer.
- **Browser mode** (any browser): data is kept in the browser's local storage and stays on your device. Clearing the browser data deletes it, so download an Excel copy from time to time.

## Notes

- The interface language is Hebrew.
- The page includes the [SheetJS](https://sheetjs.com/) library for reading and writing Excel files.

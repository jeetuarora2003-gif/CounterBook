# CounterBook

**Offline retail billing, stock and account management for Windows.**

CounterBook supports a keyboard-oriented sales counter with local data storage, invoices, purchases, returns and customer/supplier balances.

## Technology
React · TypeScript · Electron · Node.js · SQLite · Vite

## Implemented workflows
- Sales invoices, estimates, purchases, sales returns and expenses.
- Transaction-based updates to stock, payments and party balances.
- GST calculations, thermal receipts and financial-year invoice numbering.
- Product search, CSV imports, stock adjustments and low-stock reports.
- Customer purchase history, customer/supplier ledgers and local backups.
- Barcode labels, PIN login and a phone-browser barcode scanner over local Wi-Fi.

## Architecture
React screens communicate with an Electron/Node.js backend through IPC. SQLite stores products, stock movements, invoices and account entries. The optional phone scanner uses a local web server to send scanned codes to the desktop counter.

## Project status
A working foundation with a local Windows package. This is an independent development project; production deployment, scanner compatibility and printer compatibility are not claimed here.

## Relationship to Drape
CounterBook explores general shop billing. Drape focuses on apparel-specific workflows such as size-and-colour stock, alterations, exchanges and customer loyalty.

## About this repository
This is a public project showcase. Application source and business data are not distributed here. It does not contain a downloadable app or an App Store / Google Play release.

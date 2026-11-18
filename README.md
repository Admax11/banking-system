# ADMAX Banking Management System — Demo

A browser-based prototype for demonstrating common banking-office workflows.

## Upgraded features
- Dashboard with sample activity chart and summary figures
- Customer registration, directory search, and account counts
- Savings and current demo account register with search and type filter
- Simulated deposits and withdrawals with balance checks
- Printable simulated transaction receipts
- Transaction search and CSV export
- Demo loan request register with a reviewed status
- Printable management summary
- Downloadable JSON backup and restore
- Stricter validation when restoring demo backups (record limits, duplicate-ID checks, valid references, and numeric checks)
- Reset to fictional sample records
- Ghana cedi (GHS) display and responsive layout

## Run
Open `index.html` in a modern browser, or publish the repository with GitHub Pages.

## Important safety and scope
This is a learning/demo prototype only. It does not connect to a bank, hold funds, execute real transfers, verify identities, or make real lending decisions. Data is stored in the current browser's local storage and is not a secure database. It is not a secure admin system. Browser local storage can be read or changed by someone with access to the device/browser profile. The backup validation only checks demo-file structure; it does not provide authentication, encryption, tamper protection, or server-side authorization. Use fictional sample records only. Do not enter real customer details, passwords, PINs, card details, or account credentials.

A production financial service requires appropriate licensing, regulated banking/payment partners, professional security engineering, independent testing, privacy controls, and legal/regulatory review.

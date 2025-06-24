# 📄 Invoice Processing Bot (UiPath)

This UiPath automation project processes invoices received via email, extracts relevant data, updates an Excel log, and notifies corresponding suppliers via email.

##  Features

- Connects to Gmail inbox (label: `RPA`) via IMAP
-  Automatically downloads invoice attachments
- Extracts key data (e.g., supplier name, invoice date, amount)
- Logs extracted data to an Excel file
- Sends email notifications to suppliers with extracted invoice details
- Uses **custom regex patterns** per supplier or invoice type *(manual setup required)*

## Technologies Used

- [UiPath Studio](https://www.uipath.com/studio)
- IMAP & SMTP protocols
- Excel Activities
- Regex / string parsing for data extraction

##  Prerequisites

- A Gmail account with:
  - [IMAP enabled](https://support.google.com/mail/answer/7126229)
  - A label named `RPA` visible in IMAP
  - [App password](https://support.google.com/accounts/answer/185833?hl=en) if using 2FA
- UiPath Studio (2020.10+ recommended)
- Internet access for email services


# order-automation-script-capstone
Automation script for handling orders from clients/customers through google forms sending the order data to google sheets for data storage then google apps script handles data QC(Invalid Email, Possible Blank Cells, Negative numbers) and invoice generation then sends an email confirmation to the customer, script triggers when the google form connected to the script submits a data to the linked spreadsheet.

## What it does
- Reads new form submissions from a linked Google Sheet
- Copies the Invoice Template from Drive and fills all placeholders
- Sends a confirmation email to the customer
- Writes the document URL back to the Sheet row

## Skills demonstrated
- Google Apps Script (SpreadsheetApp, DocumentApp, GmailApp, DriveApp)
- Batch read/write with getValues() / setValues()
- Template automation with replaceText()
- Error handling with try/catch
- Form submission triggers

## Technologies
- Google Apps Script
- Google Forms
- Google Sheets
- Google Docs
- Gmail

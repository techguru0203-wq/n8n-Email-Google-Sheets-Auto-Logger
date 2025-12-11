# 📘 **README — Email to Google Sheets (n8n_email_to_sheets)**

# n8n Automation — Email to Google Sheets Logger

This repository contains an n8n workflow that extracts email fields  
(sender, subject, body) and logs them into a Google Sheet.

---

## 🚀 Workflow Summary
1. Manual Trigger  
2. Extract mock email data (Function Node)  
3. Append row to Google Sheets  

---

## 📂 Project Structure
```text
n8n_email_to_sheets/
├── workflows/
│ └── workflow.json
├── docs/
│ └── sample_output.json
└── README.md
```

---

## 📥 Importing Workflow
`**In n8n**`:

**Settings → Import Workflow → Select `workflow.json`**

---

## 🔧 Setup Required
- Replace Google Sheets credential placeholders  
- Replace mock email extraction with real IMAP/Email Trigger if needed  

---

## 📜 Notes
This project is ideal for demonstrating automation + data logging capabilities.

---

`**Notes**`
- Replace the placeholder credentials in the Google Sheets node with your own Google credentials.
- Replace the IMAP/Email Trigger settings with your mailbox settings if you want a live trigger.
- For demo/presentation you can trigger the flow manually after importing.

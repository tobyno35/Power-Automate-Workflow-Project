# 📋 Automated Form Submission & Notification Workflow

A trigger-based automation project built to demonstrate real-world workflow automation skills — connecting a web form, an email notification system, and a data logging spreadsheet using modern no-code/low-code tools.

---

## 🎯 Purpose

This project simulates an automated intake and logging system — the kind used in business environments to capture requests, notify the right people instantly, and maintain a clean record of all submissions without manual effort.

Built as part of my apprenticeship preparation for a Software Engineer Apprentice role focused on Digital Manufacturing and workflow automation.

---

## 🛠️ Tech Stack

| Tool | Role |
|------|------|
| Google Forms | Collects user form submissions |
| Make.com | Automation engine — connects all tools together |
| Gmail | Sends automatic email notification on each submission |
| Google Sheets | Logs all form data in real time |

---

## ⚙️ How It Works

1. A user submits the **Allegion Request Form** (Full Name, Email Address, Request Details)
2. **Make.com** detects the new submission via a scheduled trigger (every 15 minutes)
3. An **automatic email notification** is sent to the inbox confirming the submission
4. The submission data is **logged to a Google Sheets spreadsheet** with 4 columns:
   - Timestamp
   - Full Name
   - Email Address
   - Request Details

---

## 📸 Project Screenshots

### Google Form Layout
![Form Overview](PASTE-LINK-HERE)

### Live Test Submission
![Form Submission](PASTE-LINK-HERE)

### Make.com Automation Scenario (3 Connected Modules)
![Make Scenario](PASTE-LINK-HERE)

### Email Notification Received
![Email Notification](PASTE-LINK-HERE)

### Google Sheets Data Log
![Sheets Log](PASTE-LINK-HERE)

---

## 🚀 How to Run It Yourself

1. **Create a free Make.com account** at [make.com](https://make.com)
2. **Create a Google Form** with these fields:
   - Full Name (Short answer)
   - Email Address (Short answer)
   - Request Details (Paragraph)
3. **Create a Google Sheet** with columns: Timestamp, Full Name, Email Address, Request Details
4. **Build the Make.com scenario** with 3 modules:
   - Module 1: Google Forms — Watch Responses
   - Module 2: Gmail — Send an Email
   - Module 3: Google Sheets — Add a Row
5. **Connect and map the fields** between modules
6. **Run a test submission** and verify the email arrives and the sheet updates

---

## 🧠 What I Learned

- How trigger-based automation works — one event starts a chain reaction across multiple apps
- How to connect and map data between different platforms using an automation engine
- The importance of testing each module independently before running the full flow
- How to pivot and problem-solve when the originally planned tools (Microsoft Power Automate) had account-level restrictions — I found an alternative stack that demonstrated the same core concepts and delivered a working solution

The ability to identify a blocker, adapt the approach, and still deliver is a skill I'm proud of from this project.

---

## 📌 Relevance to Software Engineering Roles

This project demonstrates:
- ✅ Understanding of trigger-based automation logic
- ✅ Connecting multiple applications via integration platforms
- ✅ Systematic data logging and documentation
- ✅ Problem-solving under real-world tool constraints

---

## 👤 Author

**Oluwatobiloba "Toby" Orisadare**
AWS re/Start | Per Scholas
[LinkedIn](https://www.linkedin.com/in/toby-orisadare/)

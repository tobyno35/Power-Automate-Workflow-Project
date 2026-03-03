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
![Form Overview](https://github.com/user-attachments/assets/3f4b1a26-84fa-41b1-a381-becc014a95cc)

### Live Test Submission
![Form Submission](https://github.com/user-attachments/assets/3345d5bb-721a-4a6e-a878-95e903dbb06a)

### Make.com Automation Scenario — Full Flow
![Make Scenario](https://github.com/user-attachments/assets/a1b1dca0-3637-4e57-8bc4-0f1f317d8849)

### Make.com Module Detail
![Make Module Detail](https://github.com/user-attachments/assets/fa7722b1-b355-4694-95d5-e82695b1921c)

### Email Notification Received
![Email Notification](https://github.com/user-attachments/assets/8fe29f3c-c0ee-4a88-9e51-be27e04b397a)

### Google Sheets Data Log
![Sheets Log](https://github.com/user-attachments/assets/40d573c0-3b45-4554-8ec9-3ecbbd8add9b)

### Successful Test Run Confirmation
![Test Run](https://github.com/user-attachments/assets/415119d9-f895-4eb6-ae9e-1c5b8cb36817)

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

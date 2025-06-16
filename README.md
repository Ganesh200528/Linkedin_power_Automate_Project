# 🔄 LinkedIn Connection Automation using Power Automate

This Power Automate project automates the process of tracking and responding to new LinkedIn connections. It helps streamline job exploration by saving connection details, sending follow-up emails, handling responses, and notifying the user through mobile alerts.

---

## 📋 Features

- Manual data entry using Power Automate mobile app
- Data fields stored in Excel:
  - Name
  - Email
  - Company
  - Location
  - Position
  - Date of LinkedIn connection
- Automated email to each new connection
- Response handling using **Approval Trigger + Switch Logic**
- Mobile notifications at every stage
- Full status tracking and documentation

---

## 🧠 Response Handling Logic

### ✅ Case 1: If They Reply
- The recipient responds to the email.
- Actions:
  - The current time is recorded.
  - The response message is saved.
  - A mobile notification is sent to the user.

### ⏳ Case 2: If No Reply After 7 Days
- No response is received within 7 days.
- Actions:
  - The time is logged.
  - A "no reply" condition is triggered.
  - A mobile notification informs the user.

### 🚫 Case 3: No Hiring Process
- The recipient responds indicating no current hiring.
- Actions:
  - The message is saved with a "No hiring process" note.
  - A mobile notification is sent.

---

## ✅ Benefits

- Saves time in manually tracking responses
- Maintains a professional approach to job exploration
- Centralizes data in Excel
- Sends real-time mobile alerts
- Reduces human error with automated decision-making
- Improves follow-up consistency
- Keeps a historical record of outreach and replies

---

## 📌 Conclusion

This flow provides an efficient, structured, and professional way to manage LinkedIn job outreach. By combining Excel, Outlook, and Power Automate, users can automate tedious steps and focus on what matters most: building meaningful opportunities.

**Developed by: Thatavarthi Venkata Naga Ganesh**


# n8n Client Onboarding Automation

An automated client onboarding workflow built with **n8n**.

## 🚀 Overview

This automation receives client data from a form submission, checks conditions, stores the data in a database, and sends an automated Gmail notification.

The workflow is fully event-driven and designed to streamline the client intake process.

---

## ⚙️ How It Works

1. **Form Submission Trigger**
   - Captures client information (name, phone, email, services needed, etc.)

2. **Conditional Logic (IF Node)**
   - Checks specific conditions before proceeding.

3. **Database Insert**
   - Inserts the client data into a data table.

4. **Email Notification**
   - Sends an automated Gmail message.

---

## 🛠 Technologies Used

- n8n
- Gmail API (OAuth2)
- Google Cloud Console
- Webhooks
- Conditional Logic
- Data Tables

---

## 🔐 Setup Requirements

To use this workflow:

1. Import the JSON file into n8n.
2. Configure Gmail OAuth2 credentials.
3. Enable Gmail API in Google Cloud.
4. Add your OAuth redirect URL.
5. Add yourself as a test user (if in testing mode).

---

## 📌 Use Case

This automation is ideal for:
- Agencies
- Freelancers
- Service-based businesses
- Client intake systems

---


## 👩‍💻 Author

Batoul

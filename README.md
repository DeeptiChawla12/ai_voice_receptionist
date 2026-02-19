# 🎙️ AI Voice Receptionist Automation

🎬 **[Watch Demo](https://drive.google.com/file/d/1nIMezYIR7ntrL9l0SbTo8y8OJOnb-63L/view?usp=share_link)**

An AI-powered voice receptionist system that automates appointment booking, rescheduling, cancellation, and availability checks using natural voice interactions.

This project acts as a smart front desk assistant for businesses, similar to modern AI reception systems.

---

## 🚀 Overview

The **AI Voice Receptionist** enables customers to interact with a voice agent to:

* 📅 Book appointments
* 🔁 Reschedule appointments
* ❌ Cancel bookings
* 🕒 Check availability
* 🗂 Automatically store & update records

The system ensures **real-time synchronization** between voice conversations, database records, and calendar scheduling.

---

## 🧠 How It Works

1️⃣ User interacts with the **Voice Agent**
2️⃣ AI voice system understands the request
3️⃣ n8n automation workflow processes logic
4️⃣ System checks availability & booking rules
5️⃣ Appointment data is stored & synced automatically

---

## 🔊 Voice AI Integration

This project uses:

* **Vapi** → Real-time voice agent interaction & conversation handling

This enables human-like conversations and intelligent responses.

---

## ⚙️ Automation & Backend

Automation & orchestration powered by:

* **n8n MCP Server** → workflow automation & business logic
* **Google Sheets** → appointment database
* **Google Calendar** → scheduling & event management
* **Webhooks & APIs** → real-time integration

---

## 📌 Features

### ✅ Appointment Booking

* Books appointments via voice request
* Stores details in Google Sheets
* Automatically creates calendar events

### 🔄 Reschedule Appointment

* Updates appointment time
* Syncs changes in Sheets & Calendar

### ❌ Cancel Appointment

* Removes booking from calendar
* Updates records automatically

### ⛔ Availability Check

* Checks existing bookings
* Prevents double booking
* Voice agent informs user if slot is unavailable

### 🧾 Data Recording

* Stores interaction details
* Maintains structured appointment records

---

## 🏗️ System Architecture

```
Voice User
   ↓
AI Voice Agent (Vapi)
   ↓
n8n MCP Automation Server
   ↓
Availability Check Logic
   ↓
Google Sheets Database
   ↓
Google Calendar Sync
```

---

## 🧰 Tech Stack

| Category    | Technology      |
| ----------- | --------------- |
| Voice AI    | Vapi            |
| Automation  | n8n MCP Server  |
| Database    | Google Sheets   |
| Scheduling  | Google Calendar |
| Integration | Webhooks & APIs |

---

## 💼 Real-World Use Cases

✔ Clinics & healthcare centers
✔ Salons & beauty services
✔ Customer support desks
✔ Appointment-based businesses
✔ AI-powered virtual reception systems

---

## 🔐 Data Handling & Safety

* Prevents double booking conflicts
* Ensures real-time synchronization
* Maintains structured & consistent records
* Secure workflow-based data handling

---

## ⚡ Setup & Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/ai-voice-receptionist.git
cd ai-voice-receptionist
```

### 2️⃣ Setup n8n MCP Server

* Install n8n
* Import the workflow JSON
* Configure environment variables & webhook URLs

### 3️⃣ Configure Google Services

✔ Create Google Sheet for appointments
✔ Connect Google Calendar API
✔ Enable API credentials

### 4️⃣ Configure Vapi Voice Agent

* Create voice assistant in Vapi dashboard
* Connect webhook to n8n endpoint
* Configure intents & responses

### 5️⃣ Run Automation

Start n8n server and test voice interactions.

---

## 🧪 Example Voice Commands

🗣️ “Book an appointment tomorrow at 3 PM”
🗣️ “Reschedule my booking to Friday morning”
🗣️ “Cancel my appointment”
🗣️ “Do you have availability this afternoon?”



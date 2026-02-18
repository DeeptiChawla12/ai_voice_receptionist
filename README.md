# 🎙️ AI Voice Receptionist Automation

An AI-powered voice receptionist system that automates appointment booking, rescheduling, cancellation, and availability checks using voice interactions.

This project acts as a smart front desk assistant for businesses, similar to solutions powered by Vapi.

---

## 🚀 Overview

The AI Voice Receptionist allows users to interact with a voice agent to:

* 📅 Book appointments
* 🔁 Reschedule appointments
* ❌ Cancel bookings
* 🕒 Check availability
* 🗂 Automatically store and update records

The system ensures real-time synchronization between voice interactions, database records, and calendar scheduling.

---

## 🧠 How It Works

1. User interacts with the **Voice Agent**
2. Voice agent processes requests via AI voice tools
3. n8n MCP server handles automation logic
4. System checks availability & booking rules
5. Data is stored and synced automatically

---

## 🔊 Voice AI Integration

This project uses:

* **Vapi** → real-time voice agent interaction

These tools enable human-like conversations with users.

---

## ⚙️ Automation & Backend

Automation is powered by:

* n8n MCP Server for workflow orchestration
* Google Sheets for appointment records
* Google Calendar for scheduling

---

## 📌 Features

### ✅ Appointment Booking

* Books appointment via voice request
* Stores data in Google Sheets
* Automatically adds event to Google Calendar

### 🔄 Reschedule Appointment

* Updates appointment time
* Syncs changes in Sheets & Calendar

### ❌ Cancel Appointment

* Removes booking from calendar
* Updates records in Google Sheets

### ⛔ Availability Check

* Checks existing bookings
* Prevents double booking
* Voice agent informs user if slot is unavailable

### 🧾 Data Recording

* Stores user interaction details
* Maintains structured appointment records

---

## 🏗️ System Architecture

Voice User → AI Voice Agent → n8n MCP Server →
→ Availability Check → Google Sheet Database → Google Calendar Sync

---

## 🧰 Tech Stack

* AI Voice: Vapi
* Automation: n8n MCP Server
* Database: Google Sheets
* Scheduling: Google Calendar
* Integration: Webhooks & APIs

---

## 💼 Real-World Use Cases

✔ Clinics & healthcare centers
✔ Salons & service businesses
✔ Customer support front desks
✔ Appointment-based businesses
✔ AI-powered virtual receptionists

---

## 🔐 Data Handling & Safety

* Prevents double booking conflicts
* Ensures real-time updates
* Maintains structured data records

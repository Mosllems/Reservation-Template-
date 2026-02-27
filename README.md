# 🤖 AI-Powered Booking System

### **n8n + Gemini + ManyChat + Google Calendar**

An intelligent, automated appointment booking system designed for shops. This system analyzes customer messages on Instagram, determines their intent, checks real-time availability, and books slots directly into **Google Calendar**.

---

## 🚀 Key Features

* **Smart Intent Classification:** Distinguishes between greetings, service inquiries, and actual booking requests using a strict NLP logic.
* **Hallucination-Free Logic:** Implements a strict protocol to ensure the AI only confirms slots that are truly vacant.
* **Automated Customer Flow:** Provides a seamless end-to-end experience from the first "Hello" to a confirmed appointment.

---

## 📸 Visualizing the Workflow

### 1. The Full Automation Map

The core engine where ManyChat, Gemini, and Google Calendar interact to process every message.

### 2. AI Logic & Classification

A deep dive into how the system maps user input to specific action IDs (1: Talk, 2: Info, 3: Booking).

### 3. Google Calendar Sync

Live view of an appointment successfully captured and scheduled by the AI.

---

## 🛠 Tech Stack

* **n8n:** Workflow automation engine.
* **Gemini API:** High-precision LLM for natural language understanding.
* **ManyChat:** Omnichannel chat marketing platform.
* **Google Calendar API:** Real-time scheduling and event management.

---

## 📜 How to Use

1. Clone this repository.
2. Import the `.json` workflow file into your n8n instance.
3. Update the System Prompts with your specific shop details (Prices, Address, Services).
4. Connect your ManyChat trigger and start booking!

---

Connect your ManyChat trigger and start booking!

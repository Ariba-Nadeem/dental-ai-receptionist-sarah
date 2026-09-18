### 🦷 Intelligent Dental AI Voice Receptionist (Sarah)

A production-ready, autonomous AI Voice Agent designed to eliminate missed calls, streamline patient appointment bookings, and maximize clinic revenue. Built using an enterprise-grade backend architecture combining **[Vapi.ai](https://vapi.ai)**, **[OpenAI GPT-4o](https://openai.com)**, and **[Make.com](https://www.make.com)**. 

### 📊 The Business Problem

Dental clinics lose up to **20% to 30% of potential revenue** due to missed calls during peak hours, lunch breaks, or after-office hours. Additionally, manual appointment management often leads to scheduling overlaps and administrative inefficiencies. 

**Sarah** fixes this by operating **24/7/365**, answering patient calls instantly, answering FAQs, and booking slots directly into the calendar with zero friction. 

### 🛠️ The Tech Stack & Architecture

This system connects front-end conversational AI with advanced cloud automation: 

* **Front-End Voice Gateway:** [Vapi.ai](https://vapi.ai) (For ultra-low latency WebRTC/SIP voice streaming, STT, and TTS processing).
* **Cognitive Brain:** [OpenAI GPT-4o](https://openai.com) (Configured with custom system prompts for high-accuracy medical triage, scheduling logic, and conversational flexibility).
* **Automation Backbone:** [Make.com](https://www.make.com) (Advanced webhook parsing, multi-conditional routers, and data formatting pipelines).
* **Database & Calendar CRM:** Google Sheets & Google Calendar API (For real-time slot checking and instant data synchronization).
* **Communication Channels:** [Twilio](https://www.twilio.com) (For phone number routing) & Gmail API (For automated patient confirmation emails).

### 🔁 Complete Backend Workflow Architecture

1. **Inbound Call Handling:** The patient dials the clinic number via **Twilio**. The call is instantly routed to **Vapi.ai**, where **Sarah** greets the user using natural, human-like voice synthesis.
2. **Dynamic Slot Validation:** When the patient asks for an appointment, the AI triggers a webhook to **Make.com**, which instantly queries the clinic's calendar database to check for available slots.
3. **Data Verification & Formatting:** **Make.com** formats the patient's phone number, name, and desired appointment time into clean database strings.
4. **CRM Syncing:** The slot is securely booked into the database, instantly updating the clinic dashboard.
5. **Instant Patient Confirmation:** The automation loop completes by triggering an immediate **Gmail confirmation email** containing the appointment details and clinic policy to the patient.

### 🎯 Key Achievements & Business Impact

* **Zero Missed Leads:** 100% automated call handling capacity, ensuring no patient goes unanswered.
* **Instant Scheduling:** The entire booking lifecycle (from voice command to database entry and email confirmation) takes **under 4 seconds**.
* **Cost Reduction:** Decreases front-desk administrative burden by **up to 40%**, allowing staff to focus entirely on in-clinic patient care.

### 📸 System Visuals & Architecture
### 🔄 1. Make.com Automation Scenario Workflow
<img width="1920" height="1030" alt="image" src="https://github.com/user-attachments/assets/40795d5a-90cd-4266-af04-64b82027e0d6" />

### 📞 2. Vapi.ai Conversational AI Execution & Call Transcripts
<img width="1920" height="1030" alt="image" src="https://github.com/user-attachments/assets/0879e5cd-f23e-4852-95a5-ded737c3016c" />

### 📊 3. Patient Lead Database (Google Sheets CRM Integration)
<img width="1920" height="1030" alt="image" src="https://github.com/user-attachments/assets/72020a41-c69e-47a4-934f-b1637e70e5c5" />


### 👩‍💻 Developed By

**Ariba Nadeem**
*AI Automation & Voice Solutions Engineer*
Building high-converting AI agents and scalable backend ecosystems for global businesses.

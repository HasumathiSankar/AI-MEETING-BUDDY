# AI Meeting Buddy
### The AI-Powered Meeting Assistant

*AI Meeting Buddy* is a full-stack, AI-driven tool that automates and streamlines the entire meeting lifecycle.  
It intelligently schedules meetings across time zones, generates tailored agendas, sends automated reminders, and tracks follow-ups to improve future meetings.  
An integrated analytics dashboard provides insights to help teams plan more effectively.

---

## 🚀 Features

- *Smart Time-Zone Scheduling* – Automatically finds optimal meeting slots for participants across different countries and regions.  
- *AI-Powered Agenda Generation* – Drafts contextual, tailored agendas using previous meeting data and user inputs.  
- *Automated Reminders & Follow-Ups* – Sends notifications before meetings and tracks post-meeting tasks.  
- *Meeting History & Analytics* – Stores past meetings, satisfaction scores, and generates actionable insights.  
- *Multi-Region Time Display* – Shows the current time in each participant’s region for quick reference.  

---

## 🛠 Technology Stack

### Backend & AI
- *Python Flask* – RESTful API backend  
- *OpenAI / LLM-based NLP* – For agenda generation and content preparation  
- *Time Zone APIs* – For accurate multi-region scheduling  

### Frontend
- *React + Tailwind CSS* – Modern, responsive user interface  
- *Recharts / Chart.js* – Interactive analytics dashboards  

### Notifications & Storage
- *Email / Push Notifications* – For reminders and follow-ups  
- *SQLite / PostgreSQL* – Persistent storage for meetings, tasks, agendas, and analytics data  

---

## ⚙️ How It Works

### 1. Smart Scheduling
1. Enter participants’ countries or time zones.  
2. The system suggests the best common time slots.  
3. Confirm and save the meeting.  
4. The dashboard shows current times and the scheduled slot.  

### 2. AI Agenda Generation
- Before the meeting, the system calls the AI engine with past topics and notes.  
- A contextual, tailored agenda is drafted automatically.  
- Users can refine and finalize the agenda in the UI.  

### 3. Automated Reminders & Follow-Ups
- Reminders are sent automatically (e.g., one day and one hour before the meeting).  
- After the meeting, tasks and overdue items are tracked and follow-ups sent.  

### 4. Past Meetings & Analytics
- All meetings are stored with outcomes, attendance, and satisfaction scores.  
- The dashboard visualizes trends to improve future scheduling and agendas.  

---

## 🔮 Future Enhancements
- *User Accounts & Roles* – Authentication and multi-user support  
- *Calendar Integrations* – Sync with Google Calendar, Outlook, etc.  
- *AI Meeting Summaries* – Automatic transcripts and highlights  
- *Real-Time Collaboration* – Shared notes and live agenda editing during meetings  


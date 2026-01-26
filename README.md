# Red Flags Dashboard
<img width="3788" height="1829" alt="Screenshot 2026-01-22 110745" src="https://github.com/user-attachments/assets/e4478985-91ad-4dd1-9a4a-9ddb31f95b64" />


The **Red Flags** UI is a modern **Security Incident Dashboard** for log flows and anomaly detection results. Users can filter analyzed logs according to specific time ranges and assigned severity scores. The frontend is built using**TailwindCSS** and **Alpine.js**, and connects to a **FastAPI** backend.

---

## Screenshot
<img width="3055" height="1882" alt="Screenshot 2026-01-22 110758" src="https://github.com/user-attachments/assets/42a4e4ee-7d25-4b12-915f-5cfddd75463a" />

<img width="3748" height="1321" alt="Screenshot 2026-01-22 110815" src="https://github.com/user-attachments/assets/61405d20-9e9f-47a0-817b-b53319be113a" />

---

## Features

- **Live Logs Tab:**  
  - Search for logs by specifying severity levels, host-names and log types.  
  - Obtain pre-analysis and analyzed logs.  
  - Obtain detection analysis results by clicking to the desired analyzed log.  
  - Determine how many logs to fetch.  

- **Analytics Tab:**  
  - Gather information for last N hours.  
  - Get graphical distribution of severity levels.  
  - See top source hosts.  

- **Responsive Design:** Designed to work for both desktop and mobile devices.  
- **Dark Mode Friendly:**  

---

## Installation

### Backend (FastAPI)

1. Clone the repo:
```bash
git clone https://github.com/ekAn97/redflags-ui.git
cd redflags-ui

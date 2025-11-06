# 🎓 Focus Log Timer

> This tool is built on a simple principle: **Accountability drives progress.** It's a minimalist web app that merges the Pomodoro Technique with a mandatory activity log, helping you track your focus and build a tangible record of your accomplishments.



This app is designed for students, developers, writers, and any professional who needs to perform deep work. By prompting for a log entry after each focus session, it bridges the gap between "feeling busy" and "being productive."

---

### ✨ Key Features

* **User Authentication:** A secure login/signup system to save and protect your personal focus history.
* **Pomodoro Timer:** A clean, JavaScript-based timer (e.g., 25-min focus, 5-min break) with audio/visual cues.
* **Mandatory Activity Log:** When a focus session ends, a prompt *requires* you to log what you accomplished before the break can begin.
* **Productivity History:** A simple dashboard that visualizes your focused time and lists all past log entries, grouped by day.
* **Data-Driven Insights:** A simple report showing your most productive days or total time focused.

### 💻 Tech Stack

* **Backend:** Python (Flask/FastAPI) / Java (Spring Boot)
* **Database:** PostgreSQL / SQLite (to store user accounts and log entries)
* **Frontend:** HTML, CSS, JavaScript (JS handles all timer logic and API calls)

---

### 🚀 Getting Started

1.  Clone this repository.
2.  **Backend Setup:**
    ```bash
    cd server
    pip install -r requirements.txt
    # Set up .env and database
    python app.py
    ```
3.  **Frontend Setup:**
    ```bash
    cd client
    # Open index.html in your browser or use a live server
    ```

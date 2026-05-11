[readme.md](https://github.com/user-attachments/files/27597342/readme.md)
\# Gmail Automation Script 📧



A Python-based background automation tool that sends scheduled emails using the Gmail API and logs transaction history. Developed as part of my 2nd Internship Task.



\## ✨ Features

\- \*\*Gmail API Integration:\*\* Uses OAuth 2.0 for secure authentication.

\- \*\*Automated Scheduling:\*\* Utilizes the `schedule` library for background task management.

\- \*\*Transaction Logging:\*\* Automatically records recipient, timestamp, and status to a local CSV file.

\- \*\*Token Persistence:\*\* Stores session tokens locally to avoid repeated logins.



\## 🚀 Setup Instructions

1\. \*\*Google Cloud Setup:\*\*

&#x20;  - Enable Gmail API.

&#x20;  - Configure OAuth Consent Screen.

&#x20;  - Download `credentials.json` to the root folder.

2\. \*\*Environment:\*\*

&#x20;  - Create a virtual environment: `python -m venv .venv`

&#x20;  - Activate it: `.\\.venv\\Scripts\\Activate.ps1`

&#x20;  - Install dependencies: `pip install -r requirements.txt`

3\. \*\*Run:\*\*

&#x20;  - Execute `python main.py`.



\## 🛠️ Tech Stack

\- Python 3.x

\- Google API Client Library

\- Schedule Library

"To run this, you must provide your own credentials.json from the Google Cloud Console"


✅ backend/README.md
markdown
Copy
Edit
# Backend – GenAI Chatbot (FastAPI + Gemini)

This is the backend for the GenAI Chatbot built using FastAPI. It connects with Google’s Gemini API to provide both normal chat and PDF-based Q&A.

## Setup Instructions

1. **Clone the repo and go to the backend folder:**
   ```bash
   cd backend
Create a virtual environment and activate it:

bash
Copy
Edit
python -m venv venv
source venv/bin/activate     # On Windows: venv\Scripts\activate
Install required packages:

bash

Copy
Edit
pip install -r requirements.txt
Create a .env file and add your Gemini API key:

ini
Copy
Edit
GEMINI_API_KEY=your_key_here
Run the backend server:

bash

Copy
Edit
uvicorn main:app --reload
Backend will start at http://localhost:8000

yaml
Copy
Edit

---

### ✅ `frontend/README.md`

```markdown
# Frontend – GenAI Chatbot (React)

This is the React-based frontend for the GenAI Chatbot. It supports normal chat and PDF upload for document-based Q&A.

## Setup Instructions

1. **Go to the frontend folder:**
   ```bash
   cd frontend
Install dependencies:

bash
Copy
Edit
npm install
Start the development server:

bash
Copy
Edit
npm run dev
Frontend will run at http://localhost:5173

Note:
Make sure the backend URL inside your fetch calls (in App.js or api.js) points to:

arduino
Copy
Edit
http://localhost:8000
or your deployed backend URL (e.g., Render.com).

yaml
Copy
Edit

---

Let me know if you want a single combined README or want to add screenshots or deployment steps.








Ask ChatGPT
You said:

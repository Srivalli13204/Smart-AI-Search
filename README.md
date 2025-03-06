# Smart-AI-Search

This is an AI Powered search tool that retrieves results from **Google, YouTube, and LinkedIn**, processes them using NLP, and presents structured resukts in a React UI.

## Features
- AI enhanced query processing
- Multi-source search ( Google, YouYube, LinkedIn )
- Interactive and responsive UI
- NLP powered result ranking

## Tech Stack
- **Frontend :** React.js
- **Backend :** Django + DRF
- **Database :** MySQL
- **Deployment :** Vercel (Frontend) & Render (Backend)

1. Github repository
   https://github.com/Srivalli13204/Smart-AI-Search/

2. Setup Backend (Django)
   cd backend
   python -m venv venv
   venv\Scripts\activate
   pip install -r requirements.txt
   python manage.py migrate
   python manage.py runserver
   The API will be running at http://127.0.0.1:8000/

3. Setup Frontend (React)
   cd frontend
   npm install
   npm start
   The UI will be running at http://localhost:3000/

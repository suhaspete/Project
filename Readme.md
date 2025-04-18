you can run both the frontend and backend of your project on your Windows machine:

1. Run the Backend (FastAPI)

Open a terminal and navigate to your backend folder:

cd C:\Users\BMSIT\Pictures\xyayogn\xzayogn-client-backend-main



Create and activate a virtual environment (if not already activated):

python -m venv venv

.\venv\Scripts\activate

pip install -r requirements.txt



Start the backend server:



uvicorn app.main:app --reload



The backend will be available at: http://127.0.0.1:8000 .\venv\Scripts\Activate





2. Run the Frontend (Vite + React) Open a new terminal and navigate to your frontend folder:

npm install

npm run dev

The frontend will be available at: http://localhost:5173 3. Access the Applications Open your browser and go to: Frontend: http://localhost:5173 Backend API docs: http://127.0.0.1:8000/docs Both servers are running for you right now! 

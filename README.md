
---


# 📧 Email Manager Application

## 📋 Summary

This application is a simple email management platform with a **CRUD backend built in Python using Flask**. The frontend, built with React, provides a clean and responsive interface that communicates with the backend via a RESTful API, ensuring efficient and dynamic data flow.

---

## ⚙️ Setup

### 🔧 Backend Setup (Flask API)

1. Navigate to the `backend` folder:
   ```bash
   cd backend


2. Create and activate a virtual environment:

   * Create the virtual environment:

     ```bash
     python -m venv venv
     ```

   * Activate the virtual environment (on Windows PowerShell):

     ```bash
     .\venv\Scripts\Activate.ps1
     ```

3. Install the required Python packages:

   ```bash
   pip install flask flask-cors flask-sqlalchemy
   ```

4. Run the Flask application:

   ```bash
   python app.py
   ```

> ⚠️ **Note:** In Visual Studio Code, ensure that the Python interpreter points to your virtual environment. Use `Ctrl + Shift + P`, select `Python: Select Interpreter`, and choose the appropriate path from `.venv`.

---

### 🌐 Frontend Setup (React)

1. Navigate to the `frontend` folder:

   ```bash
   cd frontend
   ```

2. Install the frontend dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

---

## ⚠️ Challenges Faced

* Setting the correct Python path in VS Code to ensure the virtual environment (`venv`) was used properly

```



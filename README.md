## 🚀 Getting Started Relovio (Local Development)

To run this project locally, you will need **Python 3.12+**, **Node.js 20+**, and **npm** installed on your machine.

### 1. Clone the repository
```bash
git clone https://github.com/NebulaStack-prog/Relovio-GS.git
cd Relovio-GS
```
### 2. Project Structure

The repository contains two main folders:

* 📁 **/backend** – Python FastAPI server, database logic, and tests.
* 📁 **/frontend** – React, TypeScript, and UI components.

### 3. Backend Setup

Navigate to the backend folder, create a virtual environment, and install dependencies:

```bash
cd backend
python3 -m venv .venv
source .venv/bin/activate  # On Windows use: .venv\Scripts\activate
pip install -r requirements.txt
```

Start the FastAPI server:

```bash
uvicorn app.main:app --reload
```

* The API will be running at http://127.0.0.1:8000.

* You can view the interactive Swagger documentation at http://127.0.0.1:8000/docs.

### 4. Frontend Setup

Open a new terminal window, navigate to the frontend folder, and install the npm packages:

```bash
cd frontend
npm install
```

Start the development server:

```bash
npm run dev
```

The application will be available at http://localhost:5173.

### 5. How to use the app

1. Open http://localhost:5173 in your browser.
2. Click "Регистрация" (Register) to create a new user.
3. Start creating moving plans, adding boxes, and generating QR codes!

© NESTIMS & SoCrazYy

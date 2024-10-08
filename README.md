# Flashcard Tool

A web-based flashcard application that allows users to view, create, edit, and delete flashcards. The frontend is built using React and is deployed on Vercel, while the backend is powered by Node.js with a MySQL database and deployed on Render.

## Features
1. View Flashcards: Navigate through flashcards with smooth transitions and flip animations.
2. Create Flashcards: Add new flashcards through the dashboard.
3. Edit Flashcards: Update existing flashcards with new questions and answers.
4. Delete Flashcards: Remove flashcards that are no longer needed.
5. Search Functionality: Easily find flashcards by searching for specific questions or answers.

## Technologies Used
1. Frontend: React, React Router, Material-UI (MUI)
2. Backend: Node.js, Express.js, MySQL
3. Deployment: Vercel (Frontend), Render (Backend)

## Deployed Application

1. Frontend: `https://flashcard-webapp.vercel.app`
2. Backend: `https://cards-dvgk.onrender.com`

## Localhost Installation

### Prerequisites
1. Node.js (v14 or above)
2. MySQL database
3. Git (optional)

### Backend Setup

1. Clone the repository:

```
git clone https://github.com/krishnas005/project.git
cd project/backend
```

Also you need to change the api call url from frontend to backend from `https://cards-dvgk.onrender.com` to `http://localhost:5000`


2. Install dependencies:

```
npm install
```

3. Create a `.env` file in the backend directory and add your MySQL database credentials:

```
DB_HOST=your_database_host
DB_PORT=your_database_port
DB_USER=your_database_user
DB_PASSWORD=your_database_password
DB_NAME=your_database_name

```

4. Run the backend server:
```
npm start
```

The backend server will start on `http://localhost:5000`


### Frontend Setup

1. Navigate to the frontend directory:
```
cd ../frontend
```

2. Install dependencies:
```
npm install
```

3. Run the frontend development server:
```
npm start
```

The frontend server will start on `http://localhost:3000`


### Access the application:

1. Navigate to `http://localhost:3000` to view the flashcards.
2. Navigate to `http://localhost:3000/dashboard` to access the dashboard for managing flashcards.


## Thank You !!!
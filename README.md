# Todo App (Django + React)

A simple but powerful Todo application built with Django as the backend and React as the frontend. This application allows users to manage their tasks with features like add, delete, update, and mark todos as completed.

## Installation

Follow these steps to get the app running on your local machine:

### Prerequisites

- Python 3.8 or higher
- pip and virtualenv
- Node.js and npm

### Setting Up the Backend

1. Clone the repository:
   ```bash
   git clone https://github.com/anayy09/Todo-App-Django-React.git
   cd Todo-App-Django-React/backend
   ```

2. Create and activate a virtual environment:
   ```bash
   virtualenv venv
   # Windows
   venv\Scripts\activate
   # MacOS/Linux
   source venv/bin/activate
   ```

3. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Migrate the database:
   ```bash
   python manage.py migrate
   ```

5. Run the Django server:
   ```bash
   python manage.py runserver
   ```

### Setting Up the Frontend

1. Navigate to the frontend directory:
   ```bash
   cd ../frontend
   ```

2. Install the necessary npm packages:
   ```bash
   npm install
   ```

3. Start the React application:
   ```bash
   npm start
   ```

The application should now be running on `http://localhost:3000`.

## Screenshots

Here are some screenshots of the Todo App in action:

![Home Page](/images/home.png)  
*Home Page*

![Django API](/images/api.png)  
*Django Dashboard*

![Search](/images/search.png)  
*Search*

# ToDoList App

## 📋 Overview
The **ToDoList App** is a web application built using **Django** that allows users to efficiently manage their daily tasks. The app provides essential features such as adding, viewing, and deleting tasks, along with user authentication for secure access.

---

## 🚀 Features

### 🔑 **Authentication**
- **Login/Logout:**
  - Users must log in to access the app.
  - Secure login and logout functionality.

### 🏠 **Home Page**
- **Welcome Screen:**
  - Displays a personalized welcome message after login.
  - Provides quick access to task management features.

### 📃 **Recent ToDo List**
- **Task Management:**
  - Users can add new tasks to the list.
  - Displays all active tasks.

### 🗂 **History**
- **Completed/Deleted Tasks:**
  - Keeps a record of completed or deleted tasks for future reference.

### 🗑 **Delete Feature**
- **Task Deletion:**
  - Users can remove tasks from the active list.
  - Deleted tasks are stored in the history section.

---

## 🖥 **Technologies Used**
- **Backend:** Django
- **Frontend:** HTML, CSS, JavaScript, Bootstrap
- **Database:** SQLite (default Django database)

---

## 🛠 **Setup Instructions**

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/todolist.git
   ```

2. Navigate to the project directory:
   ```bash
   cd todolist
   ```

3. Create a virtual environment:
   ```bash
   python -m venv venv
   ```

4. Activate the virtual environment:
   - **Windows:**
     ```bash
     venv\Scripts\activate
     ```
   - **Mac/Linux:**
     ```bash
     source venv/bin/activate
     ```

5. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

6. Run migrations:
   ```bash
   python manage.py migrate
   ```

7. Start the development server:
   ```bash
   python manage.py runserver
   ```

8. Open the app in your browser:
   ```
   http://localhost:8000
   ```

---

## ⚙️ **App Workflow**
1. **Login/Signup:** Users must log in to access the ToDoList.
2. **Add Tasks:** Users can add tasks to their to-do list.
3. **View Recent ToDo List:** Users can view their active tasks.
4. **Delete Tasks:** Users can remove completed tasks, which are moved to the history section.
5. **Logout:** Users can securely log out of the session.

---

## 📄 **Folder Structure**
```
📂 todolist
├── 📂 todolist_app
│   ├── migrations
│   ├── templates
│   ├── views.py
│   ├── models.py
│   └── urls.py
├── manage.py
├── db.sqlite3
└── requirements.txt
```

---

## 📚 **Future Enhancements**
- Add a priority feature for tasks.
- Add notifications and reminders.
- Improve UI/UX.

---

## 🤝 **Contributing**
Contributions are welcome! Feel free to submit a pull request.

---

## 📝 **License**
This project is licensed under the MIT License.

---

## 📧 **Contact**
For any inquiries, please contact:
- **Email:** yourname@example.com
- **GitHub:** [yourusername](https://github.com/yourusername)


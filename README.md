### **MyTodo - Flask To-Do Web App**

MyTodo is a simple yet powerful **To-Do web application** built with **Flask** and **SQLite**.  
It allows you to create, edit, and delete tasks with a clean and modern UI.

<img width="1919" height="968" alt="image" src="https://github.com/user-attachments/assets/e1124c3f-c65a-4fd3-b008-58906e7848d8" />


---

## 🚀 **Features**
- Add new tasks with a title and description.
- View all tasks with timestamps.
- Edit and update existing tasks.
- Delete tasks.
- Task filtering (All, Pending, Done).
- Responsive and modern UI with dark mode and light mode.
- **Deployed on Render** .

---

## 🏗 **Tech Stack**
- **Backend:** Flask (Python)
- **Database:** SQLite (via SQLAlchemy)
- **Frontend:** HTML, CSS, Jinja Templates, Bootstrap
- **Deployment:** Gunicorn + Render
- **Other Tools:** Jinja2, ZoneInfo for IST timezone

---

## 📂 **Project Structure**
<pre>
MyTodo/
├── instance/
├── static/ # CSS, JS, images
├── templates/ # HTML templates (base.html, index.html, edit.html)
├── app.py # Main Flask app
├── create_db.py # Script to initialize database
├── requirements.txt # Dependencies
├── Procfile # For Render/Heroku deployment
└── README.md
</pre>

---

## ⚙️ **Installation & Setup**
Follow these steps to run the project locally:

### **1. Clone the Repository**
    git clone https://github.com/yourusername/MyTodo.git
    cd MyTodo
  
### **2. Create Virtual Environment**
    python -m venv venv
    source venv/bin/activate   # For Linux/Mac
    venv\Scripts\activate      # For Windows
    
### **3. Install Dependencies**
    pip install -r requirements.txt
    
### **4. Initialize the Database**
    python create_db.py
    
### **5. Run the App**
    python app.py
    
The app will run on http://127.0.0.1:5000/.

### 🌍 Live Demo
MyTodo on Render - https://mytodo-a61g.onrender.com/


### 📝 License
This project is licensed under the MIT License.
Feel free to use and modify it for your own purposes.

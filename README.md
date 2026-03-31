# Food Ordering Application

A **web-based food ordering system built with Flask and SQLite**, designed to simulate real-world restaurant order management.  
The application provides full CRUD functionality, enabling administrators to efficiently manage menus, orders, and users.

---

## Admin Features

- **Menu Management**  
  Create, read, update, and delete menu items  

- **Order Management**  
  View, edit, and delete customer orders  

- **User Management**  
  Manage user profiles, including edit and delete functionality  

---

## System Features

- **Web-based Interface** powered by Flask  
- **Persistent Data Storage** using SQLite  
- **REST-like Routing** for structured functionality  
- **Lightweight & Easy Setup**, suitable for local development  

---

### Project Structure
```
food_ordering_app/
│
├── app.py                          # Main Flask application entry point
├── database.py                     # Database connection and setup
├── init_db.py                      # Initialize database schema
│
├── menu_database_sqlite.py         # Menu-related database operations
├── order_database_sqlite.py        # Order-related database operations
├── user_database_sqlite.py         # User-related database operations
│
├── templates/                      # HTML templates (Jinja2)
│ ├── base.html
│ ├── index.html
│ ├── login.html
│ ├── register.html
│ ├── profile.html
│ ├── menu.html
│ ├── display_menu.html
│ ├── add_menu.html
│ ├── edit_menu.html
│ ├── delete_account.html
│ ├── create_order.html
│ ├── take_order.html
│ ├── orders.html
│ └── order_detail.html
│
├── static/                         # Static assets (CSS)
│ └── style.css
│
├── db/                             # SQLite database storage
│ └── food_ordering.db
│
├── Procfile                        # Deployment entry point using Render
├── requirements.txt                # Python dependencies
└── README.md
```

### Tech Stack
- **Backend**: Flask (Python 3)
- **Database**: SQLite
- **Frontend**: HTML, CSS

### How to Run the Project
1.  **Clone the repository**
```bash
   git clone https://github.com/JeffersonPI/food_order_apps_sqlite.git
   cd food_order_apps_mysql
```

2. **Create a virtual environment (optional but recommended)**
```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Initialize the database**
```bash
python init_db.py
```

5. **Run the application**
 ```bash
python app.py
```

6. **Access the application**
```
Open your browser and navigate to: `http://127.0.0.1:5000`
```

### Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

### License
This project is licensed under the [MIT License](LICENSE) - see the LICENSE file for details.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


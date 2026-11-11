# ⛽ FuelPulse – Fuel Consumption Management System

FuelPulse is a web-based fuel consumption management application developed using Python and Flask. It is designed to help users manage and monitor fuel consumption information through a web interface.

## 🚀 Technologies Used

- **Python** – Backend programming
- **Flask** – Web framework
- **MySQL** – Database management
- **HTML** – Web page structure
- **CSS** – Styling
- **JavaScript** – Frontend functionality

## ✨ Features

- Web-based application
- Flask backend integration
- MySQL database connectivity
- Fuel consumption data management
- Database schema management
- Responsive web interface

## 📁 Project Structure

```text
FuelPulse/
│
├── static/              # CSS, JavaScript and static files
├── templates/           # HTML templates
├── app.py               # Main Flask application
├── requirements.txt     # Python dependencies
├── schema.sql           # Database schema
├── aiven_schema.sql     # Aiven database schema
├── render.yaml          # Render deployment configuration
├── .gitignore           # Git ignored files
└── README.md            # Project documentation
```

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/Manikanta-Narravula/FuelPulse.git
```

### 2. Open the project folder

```bash
cd FuelPulse
```

### 3. Create a virtual environment

```bash
python -m venv .venv
```

### 4. Activate the virtual environment

**Windows:**

```bash
.venv\Scripts\activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

### 6. Configure the database

- Set up your MySQL database.
- Configure the required database credentials.
- Execute the appropriate SQL schema file.
- Configure environment variables required by the application.

### 7. Run the application

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000/
```

## ☁️ Deployment

The project includes a `render.yaml` configuration for deployment using Render.

## 👨‍💻 Developer

**Venkata Manikanta Narravula**

B.Tech – Computer Science and Engineering

GitHub: [Manikanta-Narravula](https://github.com/Manikanta-Narravula)

---

⭐ If you find this project useful, consider giving it a star!

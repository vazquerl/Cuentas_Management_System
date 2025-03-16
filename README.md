Cuentas Management System is a **Point of Sale (POS)** and **Employee Management System** built using **PySide6**. This application supports different user roles, including **Owners, Managers, Cashiers, and Bakers**, with dynamic UI changes based on their permissions.

## Features

- **Role-based access control** (Owner, Manager, Cashier, Baker)
- **Point of Sale (POS)** system for transactions
- **Inventory Management** for tracking stock
- **Employee Scheduling** to assign shifts
- **Payroll System** to manage employee earnings
- **Timeclock & My Earnings** for employees to track their working hours
- **Secure Registration System** (Only Managers & Owners can register new employees)
- **Dynamic Header Navigation** based on role

---

## Installation Guide

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/cuentas-management-system.git
cd cuentas-management-system
```

### 2. Set Up a Virtual Environment

Create a virtual environment to manage dependencies.

```bash
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate  # On Windows
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

The required dependencies include:

- **PySide6** (for the UI)
- **sqlite3** (for the database)
- **bcrypt** (for password encryption)

### 4. Initialize the Database

Ensure the database is correctly set up before running the application.

```bash
python database_utils.py
```

This will create `bakery_system.db` with all required tables.

---

## Running the Application

Once installed, run the application with:

```bash
python main_ui.py
```

This will launch the **Cuentas Management System** in full-screen mode.

---

## Default Login Credentials

For initial access, use the following credentials:

| Role    | Username | Password  |
|---------|---------|-----------|
| Owner   | admin   | admin123  |
| Manager | manager | manager123 |

Other employees must be registered by an **Owner or Manager**.

---

## Usage Instructions

1. **Login:** Enter valid credentials and log in.
2. **Dynamic Menu:** Navigation buttons appear based on your role.
3. **Perform Tasks:** Access POS, Inventory, Scheduling, Payroll, etc.
4. **Logout:** Click the "Logout" button to return to the login screen.

---

## Contributing

Feel free to fork and submit pull requests. Ensure your code follows the project structure and PEP8 guidelines.

---

## License

This project is licensed under the MIT License.

---

## Contact

For questions or suggestions, reach out to vazquerl@gmatc.matc.edu or open an issue on GitHub.



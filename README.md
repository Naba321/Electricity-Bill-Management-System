# Electricity Bill Management System

## Project Overview
The **Electricity Bill Management System** is a web-based application developed during my summer internship at **Assam Power Distribution Company Ltd. (APDCL)**. This system streamlines the process of electricity bill generation, payment, and management, ensuring efficiency and transparency.

## Technologies Used
- **Backend:** Python (Django Framework)
- **Frontend:** HTML, CSS, JavaScript
- **Database:** SQLite (or any other relational database)

## Features
- **User Authentication**: Secure login and registration for customers and admins.
- **Bill Generation**: Automatic calculation and generation of electricity bills based on user consumption.
- **Online Payment**: Integration with payment gateways for bill payments.
- **Consumption Tracking**: Customers can monitor their electricity usage.
- **Admin Dashboard**: View, manage, and generate reports on users, payments, and consumption trends.

## Installation & Setup
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Naba321/Electricity-Bill-Management-System.git
   cd Electricity-Bill-Management-System
   ```

2. **Create a Virtual Environment:**
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run Migrations:**
   ```bash
   python manage.py migrate
   ```

5. **Create a Superuser (Admin Access):**
   ```bash
   python manage.py createsuperuser
   ```
   Follow the prompts to set up the admin credentials.

6. **Run the Development Server:**
   ```bash
   python manage.py runserver
   ```
   The application will be available at **http://127.0.0.1:8000/**.

## Usage
- **Customers:** Register, login, check their bills, and make payments.
- **Admin:** Manage users, generate bills, track payments, and generate reports via the admin panel.


## License
This project is open-source under the **MIT License**.

## Author
**Nabajit Das**

For any queries or collaboration, feel free to reach out!


# Vehicle_Service_Management
A web-based Vehicle Service Management System built using Django and SQLite that helps manage customers, vehicles, service appointments, technicians, inventory, efficiently.

# Vehicle Service Management System 🚗🔧

A web-based Vehicle Service Management System built using Django and SQLite to streamline automobile service center operations. The system helps manage customers, vehicles, service appointments, technicians, inventory, and billing efficiently.

## Features

* User Authentication and Role-Based Access
* Customer Management
* Vehicle Registration and Management
* Service Appointment Booking
* Technician Management
* Service Tracking and History
* Spare Parts Inventory Management
* Billing and Invoice Generation
* Admin Dashboard with Statistics

## Tech Stack

* Frontend: HTML, CSS, Bootstrap
* Backend: Python, Django
* Database: SQLite
* Tools: Django Admin, VS Code

## Project Workflow

1. Customer registers and logs in.
2. Customer adds vehicle details.
3. Service appointments are booked.
4. Admin approves appointments and assigns technicians.
5. Technicians perform services and update records.
6. Parts used are tracked from inventory.
7. Bills and invoices are generated automatically.

## Installation

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Navigate to the project directory:

```bash
cd vehicle-service-management-system
```

3. Install dependencies:

```bash
pip install django
```

4. Apply migrations:

```bash
python manage.py migrate
```

5. Create a superuser:

```bash
python manage.py createsuperuser
```

6. Run the development server:

```bash
python manage.py runserver
```

7. Open in browser:

```
http://127.0.0.1:8000/
```

Admin Panel:

```
http://127.0.0.1:8000/admin/
```

## Project Structure

```text
vehicle-service-management-system/
├── accounts/
├── customers/
├── vehicles/
├── appointments/
├── services/
├── technicians/
├── inventory/
├── billing/
├── dashboard/
├── templates/
├── static/
├── media/
├── manage.py
└── db.sqlite3
```

## Future Enhancements

* Online Payment Integration
* Email and SMS Notifications
* Service Reminders
* Vehicle Service Reports and Analytics
* Image Upload for Vehicles and Invoices

## Author

**Karri Himabindu**

## Support
Star the Repository and Follow for More

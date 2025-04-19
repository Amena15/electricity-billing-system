# ⚡ Electricity Billing System (Django-Based)

A web-based Electricity Billing System built using Django and Python. This system allows admin users to manage customer information, monitor electricity usage, and generate billing reports. It is designed for educational, demo, and small-scale utility billing management purposes.
---

## 🔧 Features

- User Authentication: Admin, customer, staff, and provider roles with secure access control.
- Customer Registration: Register new customers using Meter ID.
-Usage Tracking: Track electricity consumption with periodic updates to usage and tariffs.
-Bill Calculation: Automatic monthly bill generation based on usage and tariff rates.
-Payments and Receipts: Facilitate online payment and generate payment receipts.
-Feedback and Issues: Customers can submit feedback or report issues directly through the system.
-Admin/Staff Panel: Administrative and staff controls for managing customer accounts, viewing and managing overdue bills, and generating reports.

---

## 🛠 Tech Stack

- **Backend:** Python, Django
- **Frontend:** HTML, CSS, JavaScript 
- **Database:** SQLite 
- **Tools:** Django Admin, Django ORM, Virtualenv

---

## 🚀 Getting Started

```bash
### 1. Clone the Repository
git clone https://github.com/your-username/electricity-billing-system.git
cd electricity-billing-system

### 2. Create and Activate a Virtual Environment 
python -m venv env
# Windows
env\Scripts\activate
# macOS/Linux
source env/bin/activate

### 3. Install Dependencies
pip install -r requirements.txt

### 4. Apply Migrations
python manage.py migrate

### 5. Run the Development Server 
python manage.py runserver

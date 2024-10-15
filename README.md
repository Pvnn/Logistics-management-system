
# Fast Logistics - Flask Project

This is a simple logistics management system built as part of a learning project using the Flask web framework. The system allows users to track their package deliveries, view their transaction history, and process payments.

## Features

- User login/logout functionality
- Display of user transactions (package details, source, destination, date, status, and payment information)
- Search functionality for transactions
- Payment processing simulation
- Responsive design using Bootstrap

## Technologies Used

- **Flask** (Backend framework)
- **HTML5/CSS3** (Frontend structure and styles)
- **Bootstrap** (Responsive layout and styling)
- **SQLite** (Local development database)

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/fast-logistics.git
   cd fast-logistics

2. Set up a virtual environment:

python3 -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`


3. Install dependencies:

pip install -r requirements.txt


4. Run the Flask app:

flask run

The app will be available at http://127.0.0.1:5000/.



Usage

After running the app, visit the homepage and log in.

The user dashboard shows your current transactions.

You can search for transactions or simulate payment by clicking "Pay Now" for unpaid transactions.

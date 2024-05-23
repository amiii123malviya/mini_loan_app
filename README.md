Loan-App
Loan Application Task given by Tech-Dome

The Loan Management System is a Django web application designed to facilitate the management of loans. It allows customers to submit loan requests, admins to approve or reject loan requests, and customers to view and manage their loans.

Features
Loan Creation: Customers can submit loan requests specifying the loan amount and term.
Loan Approval: Admins can approve or reject pending loan requests.
Loan Viewing: Customers can view details of their loans.
Repayments: Customers can make repayments on their loans, updating the loan status.
HTML Templates: The application includes HTML templates for various pages, including a landing page, loan list, loan detail, repayment add, and success message.
Installation
Clone the repository:



Install dependencies:

pip install -r requirements.txt
Apply database migrations:

python manage.py migrate
Create a superuser (admin) account:

python manage.py createsuperuser
Run the development server:

python manage.py runserver
Access the application at http://localhost:8000/

Usage
Log in as an admin using the superuser account created during installation.
Approve or reject pending loan requests in the Django admin interface.
Customers can access the loan management features via the provided HTML templates.
Customers can submit loan requests, view their loans, and make repayments.
Contributing
Contributions are welcome! If you'd like to contribute to the project, please follow these steps:

Fork the repository.
Create a new branch for your feature or bug fix.
Make your changes and commit them with descriptive messages.
Push your changes to your fork.
Submit a pull request to the main repository's develop branch.

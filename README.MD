# Simple Loan Management System
Loan Application Task given by **Tech-Dome**

A loan management application built with Django, SQLite3, JavaScript, HTML, CSS, and Bootstrap 5. The system enables customers to request loans after registration, with admin approval. Customers can make monthly loan payments, and both customers and admins have dedicated dashboards.

## Features

- **User Registration:** Customers must register before requesting loans.

- **Loan Requests:** Customers can request loans, pending admin approval.

- **Admin Approval:** Admins can approve or reject customer loan requests.

- **Loan Payments:** Customers can make monthly loan payments.

- **Dashboards:** Both customers and admins have access to dedicated dashboards.

## Getting Started

1. Clone the repository: `git clone https://github.com/khushbu091/mini-loan-app.git`
Install dependencies:

    ```
    pip install -r requirements.txt
    ```

3. Apply database migrations:

    ```
    python manage.py migrate
    ```

4. Create a superuser (admin) account:

    ```
    python manage.py createsuperuser
    ```

5. Run the development server:

    ```
    python manage.py runserver
    ```
6. Access the application at [http://localhost:8000/](http://localhost:8000/)


## Usage

1. Register as a customer to request loans.
2. Admins approve or reject loan requests in the admin dashboard.
3. Customers can make monthly loan payments through the application.
4. Both customers and admins have dashboards for efficient management.

## Contributing

Contributions are welcome! Please open pull requests or issues.
## License

This project is licensed under the [MIT License](LICENSE).

---

Simplify loan management with our application. Register, request, and pay loans effortlessly. Admins, track requests and manage approvals seamlessly.

## Credits

This project was created by Khushbu Patel.
# Hospital Management System (HMS) - Laravel

The Hospital Management System (HMS) is a software program designed to help hospitals manage their activities and events efficiently. It is built specifically using the PHP Laravel framework, providing a robust and scalable solution for hospital administration.

## Donations

If you find this project helpful and would like to support its development, feel free to donate using any of the following cryptocurrencies:

- **Bitcoin (BTC)**
  - Wallet Address: `bc1qnltxtcr289evyvwtguplz25uv36xwwateqawnr`

- **Ethereum (ETH)**
  - Wallet Address: `0x6193e77e13720A4Bb96C18C060A9d0921b90Fe70`

- **Solana (SOL)**
  - Wallet Address: `5q4RyiJUxu33kGMqiwCugvcbuttq9QMNzZByJvhTwZN9`


## Features

- **Patient Management**: Manage patient information, admissions, discharges, and medical history.
- **Doctor Management**: Maintain doctor profiles, schedules, and specializations.
- **Appointment Scheduling**: Book, view, and manage patient appointments.
- **Billing System**: Generate and manage patient bills, payment records, and invoices.
- **Inventory Management**: Track and manage hospital inventory including medicines, equipment, and supplies.
- **User Roles and Permissions**: Define roles and permissions for different types of users such as admin, doctor, nurse, and receptionist.
- **Reports and Analytics**: Generate detailed reports and analytics on hospital operations.
- **Notifications**: Email and SMS notifications for appointments, billing, and other alerts.

## Installation

To get started with the Hospital Management System, follow these steps:

### Prerequisites

- PHP >= 8.0
- Composer
- MySQL
- Node.js and NPM

### Steps

1. **Clone the repository:**
    ```bash
    git clone https://github.com/XpertBotTeam/hospital-system-mangment
    cd hospital-system-mangment
    ```

2. **Install PHP dependencies:**
    ```bash
    composer install
    ```

3. **Install Node.js dependencies:**
    ```bash
    npm install
    ```

4. **Compile assets:**
    ```bash
    npm run dev
    ```

5. **Copy the `.env.example` file to `.env` and configure the environment variables:**
    ```bash
    cp .env.example .env
    ```

6. **Generate an application key:**
    ```bash
    php artisan key:generate
    ```

7. **Set up the database:**
    - Create a database in your MySQL server.
    - Update the `.env` file with your database credentials.

8. **Run migrations and seed the database:**
    ```bash
    php artisan migrate --seed
    ```

9. **Serve the application:**
    ```bash
    php artisan serve
    ```

10. **Access the application:**
    Open your browser and go to `http://localhost:8000`.

## Usage

### Admin Dashboard

- **Login as Admin:** Use the default admin credentials provided in the database seeder or create a new admin user.
- **Manage Users:** Create and manage users with different roles (Doctor, Nurse, Receptionist).
- **View Reports:** Access detailed reports on patient admissions, doctor performance, inventory usage, etc.

### Doctor and Nurse Dashboard

- **View Schedule:** Check daily, weekly, or monthly schedules.
- **Manage Appointments:** View and manage patient appointments.
- **Patient Records:** Access patient medical history and treatment plans.

### Receptionist Dashboard

- **Schedule Appointments:** Book and manage patient appointments.
- **Patient Registration:** Register new patients and update existing patient information.



## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

We would like to thank the Laravel community for their valuable resources and support.


Got it, here's the **Contributing** section in **plain text**, clean and copy-ready — no Markdown, no code blocks:

---

## Contributing

We welcome contributions from the community to improve the Hospital Management System!

How to Contribute:

1. Fork the repository and clone it to your local machine.
2. Create a new branch for your feature or bug fix:
   git checkout -b feature/your-feature-name
3. Make your changes and ensure everything works properly.
4. Commit and push your changes to your forked repository.
5. Open a Pull Request to the main repository with a clear explanation of your changes.

Contribution Ideas:

* Fix bugs or UI issues
* Add new features (like telemedicine support or advanced analytics)
* Improve performance or structure of the code
* Add unit tests
* Update or expand the documentation

Development Guidelines:

* Follow PSR-12 coding standards.
* Write meaningful commit messages.
* Ensure no errors after running:
  php artisan
  npm run dev

Need Help?

If you're not sure where to start, check the "Issues" tab on GitHub for labels like "good first issue" or "help wanted."

We appreciate every contribution, whether it's a bug fix, documentation update, or new feature!

---


Thank you for using the Hospital Management System. We hope it helps you manage your hospital efficiently and effectively.

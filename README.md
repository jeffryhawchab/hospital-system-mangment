
<head>
    <title>Hospital Management System (HMS) - Laravel</title>
</head>
<body>
    <h1>Hospital Management System (HMS) - Laravel</h1>
    <p>
        The Hospital Management System (HMS) is a software program designed to help hospitals manage their activities and events efficiently. 
        It is built specifically using the PHP Laravel framework, providing a robust and scalable solution for hospital administration.
    </p>

    <h2>Features</h2>
    <ul>
        <li><strong>Patient Management:</strong> Manage patient information, admissions, discharges, and medical history.</li>
        <li><strong>Doctor Management:</strong> Maintain doctor profiles, schedules, and specializations.</li>
        <li><strong>Appointment Scheduling:</strong> Book, view, and manage patient appointments.</li>
        <li><strong>Billing System:</strong> Generate and manage patient bills, payment records, and invoices.</li>
        <li><strong>Inventory Management:</strong> Track and manage hospital inventory including medicines, equipment, and supplies.</li>
        <li><strong>User Roles and Permissions:</strong> Define roles and permissions for different types of users such as admin, doctor, nurse, and receptionist.</li>
        <li><strong>Reports and Analytics:</strong> Generate detailed reports and analytics on hospital operations.</li>
        <li><strong>Notifications:</strong> Email and SMS notifications for appointments, billing, and other alerts.</li>
    </ul>

    <h2>Installation</h2>
    <p>To get started with the Hospital Management System, follow these steps:</p>

    <h3>Prerequisites</h3>
    <ul>
        <li>PHP &gt;= 8.0</li>
        <li>Composer</li>
        <li>MySQL</li>
        <li>Node.js and NPM</li>
    </ul>

    <h3>Steps</h3>
    <ol>
        <li><strong>Clone the repository:</strong>
            <pre><code>git clone https://github.com/your-username/hospital-management-system.git
cd hospital-management-system</code></pre>
        </li>
        <li><strong>Install PHP dependencies:</strong>
            <pre><code>composer install</code></pre>
        </li>
        <li><strong>Install Node.js dependencies:</strong>
            <pre><code>npm install</code></pre>
        </li>
        <li><strong>Compile assets:</strong>
            <pre><code>npm run dev</code></pre>
        </li>
        <li><strong>Copy the <code>.env.example</code> file to <code>.env</code> and configure the environment variables:</strong>
            <pre><code>cp .env.example .env</code></pre>
        </li>
        <li><strong>Generate an application key:</strong>
            <pre><code>php artisan key:generate</code></pre>
        </li>
        <li><strong>Set up the database:</strong>
            <ul>
                <li>Create a database in your MySQL server.</li>
                <li>Update the <code>.env</code> file with your database credentials.</li>
            </ul>
        </li>
        <li><strong>Run migrations and seed the database:</strong>
            <pre><code>php artisan migrate --seed</code></pre>
        </li>
        <li><strong>Serve the application:</strong>
            <pre><code>php artisan serve</code></pre>
        </li>
        <li><strong>Access the application:</strong>
            <p>Open your browser and go to <a href="http://localhost:8000">http://localhost:8000</a>.</p>
        </li>
    </ol>

    <h2>Usage</h2>
    <h3>Admin Dashboard</h3>
    <ul>
        <li><strong>Login as Admin:</strong> Use the default admin credentials provided in the database seeder or create a new admin user.</li>
        <li><strong>Manage Users:</strong> Create and manage users with different roles (Doctor, Nurse, Receptionist).</li>
        <li><strong>View Reports:</strong> Access detailed reports on patient admissions, doctor performance, inventory usage, etc.</li>
    </ul>

    <h3>Doctor and Nurse Dashboard</h3>
    <ul>
        <li><strong>View Schedule:</strong> Check daily, weekly, or monthly schedules.</li>
        <li><strong>Manage Appointments:</strong> View and manage patient appointments.</li>
        <li><strong>Patient Records:</strong> Access patient medical history and treatment plans.</li>
    </ul>

    <h3>Receptionist Dashboard</h3>
    <ul>
        <li><strong>Schedule Appointments:</strong> Book and manage patient appointments.</li>
        <li><strong>Patient Registration:</strong> Register new patients and update existing patient information.</li>
    </ul>

    <h2>Contributing</h2>
    <p>We welcome contributions to enhance the Hospital Management System. Please follow these steps to contribute:</p>
    <ol>
        <li>Fork the repository.</li>
        <li>Create a new branch (<code>git checkout -b feature/YourFeature</code>).</li>
        <li>Commit your changes (<code>git commit -m 'Add some feature'</code>).</li>
        <li>Push to the branch (<code>git push origin feature/YourFeature</code>).</li>
        <li>Open a pull request.</li>
    </ol>

    <h2>License</h2>
    <p>This project is licensed under the MIT License. See the <a href="LICENSE">LICENSE</a> file for more details.</p>

    <h2>Acknowledgements</h2>
    <p>We would like to thank the Laravel community for their valuable resources and support.</p>

    <h2>Contact</h2>
    <p>For any inquiries or support, please contact us at <a href="mailto:support@hospitalms.com">support@hospitalms.com</a>.</p>

    <hr>
    <p>Thank you for using the Hospital Management System. We hope it helps you manage your hospital efficiently and effectively.</p>

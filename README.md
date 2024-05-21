# Cyber-Cafe-Management-System<br>Using PHP & Mysql...

The Cyber Cafe Management System (CCMS) is a web-based application designed to manage the operations of a cyber cafe efficiently. It provides features for managing user accounts, computer usage, billing, and generating reports. This README file provides information on how to set up and use the CCMS application.

## Features

- User account management: Create, update, and delete user accounts.
- Computer management: Add, remove, or update computer details.
- Session tracking: Monitor computer usage sessions.
- Billing: Calculate charges based on session duration and services used.
- Reporting: Generate reports on usage, revenue, and user activity.

## Installation

1. **Download**: Clone or download the CCMS project from the repository.

2. **Extract**: Extract the contents of the downloaded zip file.

3. **Setup Database**: Create a MySQL database and import the `ccmsdb.sql` file provided in the SQL folder to set up the database schema.

4. **Configure**: Modify the `config.php` file located in the `includes` folder to set up the database connection parameters.

5. **Deploy**: Copy the extracted files to your web server's root directory (e.g., `xampp/htdocs` for XAMPP).

6. **Access**: Open your web browser and navigate to `http://localhost/ccms` (replace `localhost` and `ccms` with your server's hostname and project directory, if different).

## Usage

1. **Login**: Access the CCMS application using the provided login credentials (default admin username: `admin`, password: `admin`).

2. **Dashboard**: Once logged in, you'll be directed to the dashboard, where you can navigate to different sections of the application.

3. **Manage Users**: Use the User Management section to create, edit, or delete user accounts.

4. **Manage Computers**: Add, update, or remove computers in the Cyber Cafe using the Computer Management section.

5. **Monitor Sessions**: Keep track of computer usage sessions in real-time using the Session Tracking feature.

6. **Billing**: Generate bills for customers based on their computer usage using the Billing section.

7. **Reports**: Access various reports to analyze usage, revenue, and user activity.

## Contributors

- John Doe (@johndoe)
- Jane Smith (@janesmith)

## Support

Feel free to customize this README file based on your specific project details, such as additional setup instructions, usage guidelines, or contributor information.

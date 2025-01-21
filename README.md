---

# Library Management System (LMS)

The Library Management System (LMS) is a web-based application designed to streamline the management of library operations. It offers functionalities for librarians and staff to manage books, authors, users, and book issues. The system also allows patrons to search for and borrow books, view due dates, and pay fines for overdue items.

## Key Features

- **User Authentication**: Separate login systems for patrons and administrators. Admins have additional privileges to manage books and users, while patrons can browse and borrow books.
- **Book Catalog Management**: Admins can add, edit, or delete books from the catalog. Each book includes details such as title, ISBN, author, category, and availability status.
- **Author Management**: Admins can manage author information, add new authors, and link them to relevant books.
- **Book Issuance**: Admins can issue books to users, tracking borrow dates, due dates, and book availability.
- **Fine Management**: Automatically calculates fines for overdue books and provides options for users to pay fines.
- **Admin Dashboard**: A central hub for admins to monitor book statistics, including the total number of books, details of issued books, and user information.
- **User Management**: Admins can register new users, update user information, and deactivate accounts.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript, and PHP to create dynamic, interactive web pages.
- **Backend**: PHP to handle book issuing logic, user registration, and database management.
- **Database**: MySQL to manage data such as book records, users, authors, and transactions.
- **Security**: Role-based access control to provide secure and tailored access for patrons and admins.

## Installation Instructions

### Prerequisites

Ensure you have the following installed on your system:
- **PHP** (for backend processing)
- **MySQL** (for database management)
- **Web Server** (Apache, Nginx, or XAMPP)

### Steps to Install

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/library-management-system.git
   ```

2. **Install PHP and MySQL** if not already installed on your system.
   - You can use [XAMPP](https://www.apachefriends.org/index.html) for an all-in-one PHP, MySQL, and Apache solution.

3. **Create a MySQL database**:
   - Open `phpMyAdmin` and create a new database called `library_management_system`.
   - Import the SQL file (provided in the project) to set up the required tables for books, users, authors, etc.

4. **Configure the database connection**:
   - Open the `config.php` file and set up the database connection details (username, password, database name).

5. **Start the web server** and navigate to the project folder.
   - Open the browser and visit:
     ```
     http://localhost/library-management-system
     ```

## Usage

- **Admin Login**: Admins can log in to the admin dashboard with their credentials to manage books, users, and view system statistics.
- **Patron Login**: Patrons can register, log in, browse books, borrow books, and view fine details.
- **Book Management**: Admins can add, edit, or remove books, and track their availability.
- **Fine Payment**: Patrons can view fines for overdue books and make payments directly through the system.

## Database Structure

The system uses the following database structure:

- **Users Table**: Stores user details such as name, email, role (admin/patron), and login credentials.
- **Books Table**: Contains book details like title, ISBN, author, category, and availability status.
- **Authors Table**: Stores author information and links to books.
- **Transactions Table**: Tracks issued books, borrow dates, due dates, and overdue status.
- **Fines Table**: Calculates and stores fines for overdue books.

## Contributing

Contributions are welcome! If you want to enhance the functionality or fix bugs, feel free to fork the repository and submit a pull request. Issues and feature requests can also be created.

### Guidelines for Contribution:
- Fork the repository.
- Create a new branch for your feature/bugfix.
- Commit your changes with meaningful commit messages.
- Submit a pull request for review.

## License

This project is open-source and available under the [MIT License](LICENSE).

---

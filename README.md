# LMS
Library Management System (LMS)
This Library Management System (LMS) is a web-based application designed to manage the daily operations of a library efficiently. The system allows librarians and staff to manage books, authors, users, and book issues. It also provides patrons with the ability to search and borrow books, view due dates, and pay fines for overdue items.

Key Features:
 - User Authentication: Separate login systems for patrons and administrators. Admins have access to additional management features, while patrons can browse and borrow books.
 - Book Catalog Management: Admins can add, edit, or delete books from the catalog. Book details include title, ISBN, author, category, and availability status.
 - Author Management: Admins can manage author information, including adding new authors and associating them with books.
 - Book Issuance: Admins can issue books to users, tracking the borrow date, due date, and book availability.
 - Fine Management: Automatically calculates fines for overdue books and provides payment options.
 - Admin Dashboard: A central hub that allows admins to view book statistics, including the total number of books, issued book details, and user information.
 - User Management: Admins can register new users, update user details, and deactivate accounts.

Technologies Used:
 - Frontend: HTML, CSS, JavaScript, and PHP for creating dynamic pages.
 - Backend: PHP for handling the logic of book issuing, user registration, and database management.
 - Database: MySQL for managing data related to books, users, authors, and transactions.
 - Security: Role-based access control to ensure secure access for both patrons and admins.

Installation Instructions:
1. Clone the repository using:
git clone https://github.com/your-username/library-management-system.git

2. Install PHP and MySQL if not already installed on your system.
3. Set up a MySQL database with the necessary tables (details provided in the README.md).
4. Configure the database connection in the config.php file.
5. Open the project in your browser and start using the system.

Contributing:
Feel free to fork this repository, contribute new features, or submit issues. Contributions to enhance the functionality and user experience are always welcome!

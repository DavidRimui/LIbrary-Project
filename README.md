# PagePal

### Overview
This project is a full-stack library application developed using React.js for the frontend, Node.js with Express for the backend, and MongoDB as the database. The application allows users to sign up, log in, and manage their library activities such as issuing (borrowing) books for a specified duration. If a user fails to return a book within the designated time, a fee will be applied.

This project utilizes the Framer Motion library to enhance the user experience with captivating animations and transitions. Framer Motion is a popular animation library for React applications that provides a simple and powerful way to create fluid and engaging user interfaces.

### Features
#### User Management
- **Sign Up:** Users can create an account by providing necessary details and registering with the application.
- **Login:** Registered users can log in to access their account and library functionalities.
- **Email Verification:** A verification process is implemented to ensure the validity of user email addresses.
- **Update User:** Users have the ability to update their profile information, such as name, contact details, and password.
- **Delete User:** Users can choose to delete their account and associated data from the application.
- **Get User:** Users can view their profile information and library records.

#### Book Management
- **Add Book:** Admin users can add new books to the library by providing details such as title, author, and genre.
- **Search Book:** Users can search for books based on various criteria, such as title, author, or genre.
- **Issue Book:** Users can issue books for a specified duration, marking them as borrowed from the library.
- **Return Book:** Users can mark a borrowed book as returned once they have returned it to the library.
- **Get All Books:** Users can view a list of all available books in the library.
- **Get Non-Returned Books:** Users can see a list of books that are currently borrowed and not yet returned.
- **Get Book By ID:** Users can retrieve detailed information about a specific book using its unique identifier.

#### Password Management
- **Forget Password:** Users who forget their password can initiate a password reset process by providing their email address.
- **Reset Password:** After initiating the password reset process, users receive an email with instructions to reset their password.

#### Frontend Pages
- **Sign Up:** A page where users can create a new account by providing their details.
- **Login:** The login page where users can enter their credentials to access their account.
- **Home:** The main page where users can view featured books and access various functionalities.
- **Add Book:** A page accessible to admin users for adding new books to the library.
- **Book Details:** A page to display book details.
- **Profile:** The user profile page displaying personal information and library records.
- **Non-Returned Books:** A page that lists books currently borrowed by the user and not yet returned.
- **Issued Books:** A page displaying a user's history of issued books and their respective return status.

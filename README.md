**Personal Book Management System**

A web application that allows users to manage their offline book collections in an online database. Users can add books to their collections by entering the ISBN, and the system looks up the book's details via the OpenLibrary API and stores them in the database. The system binds the user to the book. The user can create a forum for the book to find other readers and have conversations with them.

**Installation**

To install the project, follow these steps:
Clone the repository to your local machine.
Install the required dependencies using mvn install.
Start the server using mvn spring-boot:run.

**Usage**

To use the application, follow these steps:
Navigate to the homepage of the application.
Enter the ISBN of the book you want to add to your collection.
If the book is not already in the database, the application will look up its details via the OpenLibrary API and add it to the database.
The application will bind the user to the book through the shelf entity.
Next time a different user looks up the book, if that book's details were already in the database, the system will bind that user to the book through the shelf entity.

**API Documentation**

The API documentation is available at https://docs.google.com/document/d/1m_rXsYXA3AowwNxJtpLkQSRy7jrKd-lKGvH5S296KTM/edit?usp=sharing.

**Issues**

If you encounter any issues when using the application, please report them on the GitHub Issues page. Be sure to include detailed information about the issue, including steps to reproduce it and any error messages you received.

**Code Samples**

Code samples for using the API are available at https://docs.google.com/document/d/1y774gMZr1Ck09rDIlEtuPfUqkK9Kii8jF_0rLXsQXyA/edit?usp=sharing.

**License**

The project is licensed under the MIT License. See the LICENSE file for more information.
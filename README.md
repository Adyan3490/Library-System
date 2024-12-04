A library system for a project consisting of features such as:
1. Book Management: Ability to add, remove, and search for books.
2. User Management: Ability to register users and manage their accounts.
3. Borrowing System: Ability for users to borrow and return books, with limits on how many books they can borrow.
4. Admin Functions: Privileges for an admin to add/remove books and manage user accounts

This is done using classes such as:
1. Book: Represents a book in the library, with attributes like title, author, ISBN, and status (available/borrowed).
2. User: Represents a user of the library with attributes like name, ID, and list of borrowed books.
3. Library: Acts as a central hub managing books and users, including the ability to add or remove books and users.
4. Admin: A specialised user who can perform all the functions of a normal user but has additional privileges
5. Transaction: Represents the borrowing and returning activities, recording each transaction’s details, such as date and status.

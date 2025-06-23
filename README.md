# Task_1
Library Database Schema – Summary
The library database schema is designed to efficiently manage and organize data related to books, members, borrowing activity, and fines. It consists of four main tables, each serving a specific purpose:

Book Table
Stores detailed information about each book available in the library, such as book_id, title, author, genre, and publication details.
➤ Helps identify and manage the library's book collection.

Member Table
Contains user/member information, including member_id, name, contact details, and registration data.
➤ Used to identify individuals who are part of the library and track their activity.

Borrow Table
Records borrowing transactions, including borrow_id, book_id, member_id, borrow date, due date, and return date.
➤ Helps track which member borrowed which book and whether it has been returned on time.

Fine Table
Stores fines related to overdue books, typically linked by borrow_id. It includes the fine amount and status (paid/unpaid).
➤ Helps identify overdue books and manage penalties for late returns.

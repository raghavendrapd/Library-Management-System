# Library-Management-System
This project is a simple yet functional library management system designed to help manage books, users, and borrowing activity within a small to medium-sized library. It's built to reduce the need for manual record-keeping and make the overall process of running a library more efficient and reliable.

Features
Book Inventory
Add new books, update existing ones, or remove them from the system. Each book entry includes details like title, author, category, ISBN, and whether it's currently available or checked out.

User Management
Register and manage library users, track their borrowing activity, and store essential details like contact information and active loans.

Issue and Return System
Easily issue books to users and track due dates. When a book is returned, the system updates the inventory automatically. You can also keep track of late returns and apply fines if needed.

Search and Filter
Quickly find books using the built-in search feature. You can search by title, author, or category, and filter results based on availability.

Overdue Tracking
Keep an eye on books that haven’t been returned on time. The system can generate a list of overdue items so follow-ups can be made efficiently.

Reports and Activity Logs
View useful reports like how many books are currently issued, which books are most borrowed, and a user’s borrowing history. This helps in understanding usage patterns and planning library resources.

Persistent Storage
All data is stored in a local database (like SQLite), so everything is saved between sessions. You don’t lose any information when you close the application.

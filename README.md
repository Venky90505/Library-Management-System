# Library-Management-System
Automates key library operations including book management, user accounts, borrowing, and returns. Enhances efficiency with search, due date tracking, and inventory updates, simplifying library management for users and staff.
## Project Overview
A simple Library Management System implemented in Python. This project provides a command-line interface and basic library functions such as adding, viewing, borrowing, returning, and searching for books. Data persistence is handled using CSV files.

## Features
- Add new books with title and author
- View all books in the library
- Borrow books with tracking of borrower and due date
- Return borrowed books updating the status
- Search for books by keyword in title or author
- Book status: Available or Borrowed
- Due date calculation for borrowed books (14 days from borrow date)

## Installation
- Python 3.x required
- No external packages required beyond Python standard libraries (like pandas)

## Usage
1. Clone or download this repository.
2. Run the Python script or open the Jupyter notebook `library-management.ipynb`.
3. Follow the on-screen prompts to use the library system:
   - `add`: Add a book
   - `view`: View books
   - `borrow`: Borrow a book
   - `return`: Return a book
   - `search`: Search books by keyword
4. Book data is saved automatically in `books.csv` and `borrowedbooks.csv`.

## File Structure
- `library-management.ipynb`: Main project notebook/script.
- `books.csv`: Stores library book data.
- `borrowedbooks.csv`: Stores currently borrowed book records.

## Future Enhancements
- Develop a GUI or web interface.
- Add user authentication and different user roles.
- Implement late return penalties.

## Contributing
Feel free to fork this project, submit issues, and send pull requests to improve this system.

## License
This project is licensed under the MIT License.

---

Happy reading and managing your library!

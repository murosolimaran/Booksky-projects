### **Project Overview**

The project is a simple web application called **Booksky**, designed to manage a collection of books. It allows users to add new books with a title, author, and description, and also delete books from the collection. Here’s a breakdown of the structure and functionality:

### **Structure and Functionality**

1. **HTML (index.html)**:
   - Sets up the basic structure of the application with a simple navigation bar, a container for book entries, and a popup form for adding new books.
   - The main elements include:
     - A header (`<h1>`) for the app title "Booksky".
     - A container (`<div class="container">`) that holds the book entries.
     - A popup form (`<div class="popup-box">`) that appears when adding new books, allowing users to input the book's title, author, and description.
     - An "Add" button that triggers the popup and a cancel button that closes it.

2. **JavaScript (script.js)**:
   - Manages the interactive behavior of the application, including:
     - Showing and hiding the popup form when adding a new book.
     - Adding a book to the list by capturing input data from the form and displaying it within the book container.
     - Deleting a book from the list when the "Delete" button is clicked.

3. **CSS (style.css)**:
   - Styles the application, providing a consistent and visually appealing design.
   - Key styles include:
     - The navbar is styled with a distinct background color.
     - Book entries are displayed in individual cards (`.book-container`) with black backgrounds and red titles.
     - A floating "Add" button styled as a prominent circle to easily trigger the popup form.
     - The popup form is styled to appear above a darkened overlay, enhancing the focus on adding new book details.

### **Key Features:**
- **Add Books:** Users can add books by clicking the "+" button, filling out a form, and pressing "Add".
- **Delete Books:** Each book has a "Delete" button that removes the book entry from the display.
- **Responsive Design:** The layout is designed to work across various screen sizes, with book entries displayed in a flexible inline-block format.

This application serves as a basic book management tool, demonstrating fundamental front-end skills, including DOM manipulation, event handling, and responsive styling.

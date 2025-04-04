

# Book Information Form

This project provides a simple web form for entering book details, including the book name, author, number of pages, and whether it has been read. The form appears as a modal when a button is clicked. The submitted data is added to an array and displayed in a list below the form.

## Features

- Modal form to add new book information.
- Fields for book name, author name, number of pages, and read status (checkbox).
- List of added books is displayed below the form.
- Books are stored in an array and displayed dynamically.
- Modal can be opened and closed using buttons and clicks outside the modal.

## Technologies Used

- **HTML**: Structure of the webpage and form.
- **CSS**: Styling of the page, form, button, and modal.
- **JavaScript**: Handles form submission, modal behavior, and dynamic list updates.

## Project Setup

1. Clone this repository to your local machine.

   ```bash
   git clone https://github.com/your-username/book-form-modal.git
   ```

2. Navigate to the project directory:

   ```bash
   cd book-form-modal
   ```

3. Open `index.html` in your browser to view and interact with the project.

## How to Use

1. Click the **"Add Book"** button to open the form as a modal.
2. Fill out the form with the book name, author name, number of pages, and check the "Read" checkbox if you've read the book.
3. Click **"Add Book"** in the form to submit the data.
4. The book information will be added to a list below the form, showing all the books entered.
5. To close the modal, click the **"X"** in the top-right corner or click outside the modal.

## Code Explanation

- **HTML**: Contains the form structure and the modal layout.
- **CSS**: Provides styling for the modal, form, button, and book list.
- **JavaScript**: Handles the form submission, modal opening/closing, and dynamically updating the book list.

### Modal Functionality:
- The modal is hidden by default and can be opened by clicking the "Add Book" button.
- You can close the modal by clicking the close button (X) or clicking anywhere outside the modal.

### Form Submission:
- When the form is submitted, the data is collected from the input fields and stored in an array as an object.
- The list of books is then updated and displayed on the page.

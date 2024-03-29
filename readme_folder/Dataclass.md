# Dataclass.py

## Overview
The `BookShelf` class represents a collection of books and provides functionalities to manage them such as adding, removing, updating, and searching for books.

## Attributes
- `filename`: str, name of the text file to store books
- `Books_in_my_library`: list, to store Book objects
- `existing_isbns`: set, set of existing ISBNs for validation

## Methods

### `__init__(self)`
- Initializes the `BookShelf` object.
- Initializes `filename`, `Books_in_my_library`, and loads existing books.
- Creates a set of existing ISBNs for validation.

### `loadBooks(self)`
- Loads books from the text file and populates `Books_in_my_library` list.

### `saveBooks(self)`
- Saves books from `Books_in_my_library` list to the text file.

### `getAllBooks(self)`
- Returns all books in the library.

### `removeBook(self)`
- Removes a book by its ID.

### `searchBooks(self, string)`
- Searches books by title, author, or copyright date.

### `updateBookById(self)`
- Updates book information by its ID.

### `createBook(self)`
- Creates a new book.

### `promptBookInfo(self, book=None)`
- Prompts for book information.

### `validateInput(self, prompt, field_name, validation_func)`
- Validates user input.

### `validateFloatInput(self, prompt, field_name, validation_func)`
- Validates float input.

### `validateDateInput(self, prompt, validation_func)`
- Validates date input.

### `generateUniqueIsbn(self)`
- Generates a unique ISBN.

### `menu(self)`
- Prints menu options.

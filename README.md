# sheet-music-library
A library webpage designed to hold sheet music metadata.

Continued object practice. The library will be an array of "book" objects, each containing basic metadata about the piece. I've chosen to use a muscial application, so I can a) mock data I'm familiar with and b) create interesting stretch goals.

## MVP Criteria:
- Constructor for making "book" objects
- Book objects should include:
    - Title
    - Contributor Info
    - Page Count
    - A `Played?` Checkbox
    - An `info` function which `return`s a string with a description of the book, using the object's properties.
- The library must be an array of objects
- A function outside the book constructor which takes input arguments to add a new book to the library
- A function which loops through the array of books and displays all of them simultaneously
- A "New Book" button which creates a form to enter inputs for the function to add a book
- A button to remove a corresponding book from the library.
- A button or checkbox for the `Played?` option
- Responsive

### Stretch Goals:
- Persistent data options via localstorage or Firebase
- An instruments list for each book
- Selectable ensemble types: Concert Band, Orchestra, Choir, Solo
- Edit Book function which allows the user to update an existing book
- Animations

## Process:
1. Skeleton HTML/CSS
2. Book Constructor function
3. Add Book function & button/card design
4. Create placeholder books & display all
5. Delete Book function
6. Selectable Ensembles
7. Instrument list
8. Edit Book function
9. Storage
10. Animations

## Misc.

### "Old Library" Color Swatches
Dark Slate Grey: #325453

Cadet: #517174

Fire Opal: #ef5d58

Burlywood: #dcbe87

Dark Gold: #ad6a34

French Puce: #4e1d04
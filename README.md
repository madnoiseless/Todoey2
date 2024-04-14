# Todoey

This project is a simple To-Do List application built using Node.js, Express, MongoDB, and EJS templating.

## Features
- Users can add new items to their to-do list.
- Users can mark items as completed by checking them off.
- Users can delete items from the list.
- Users can create custom lists with default items or view existing lists.
- Data is stored in a MongoDB database.

## Setup
1. Clone the repository.
2. Install dependencies using `npm install`.
3. Start the server using `npm start`.
4. Access the application at `http://localhost:3000`.

## Dependencies
- Express.js
- Body-parser
- Mongoose
- Lodash

## File Structure
- `index.js`: Entry point of the application containing server and routes setup.
- `index.ejs`: EJS template for rendering the to-do list interface.
- `partials/header.ejs`: Header partial containing HTML head section.
- `partials/footer.ejs`: Footer partial containing copyright information.
- `public/styles/main.css`: CSS file for styling the application.

## Database Schema
- `Item`: Represents individual to-do list items.
- `List`: Represents a collection of items with a custom name.

## Endpoints
- GET `/`: Displays the default to-do list or creates it if empty.
- GET `/:customListName`: Displays a custom list or creates a new one if not found.
- POST `/`: Adds a new item to the list.
- POST `/delete`: Deletes a checked item from the list.

## Acknowledgements
- Icons provided by Font Awesome.
- Fonts obtained from Google Fonts.

---

Feel free to explore the codebase and make any improvements or modifications as needed. If you encounter any issues or have feedback, please let us know. Thank you for using our To-Do List application!

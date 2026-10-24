# College Lost & Found System

## About the Project

The **College Lost & Found System** is a simple web-based project designed to help users report items they have lost or found on campus. Users can enter item details, search for items by name, view the available item list, and delete an item when needed.

## Features

- **Report Lost Item:** Enter the item name, description, location, date, and contact number.
- **Report Found Item:** Enter details about an item that has been found.
- **Search Items:** Search for items by name.
- **Show All Items:** Display all items saved in the application.
- **Delete Item:** Remove an item after confirmation.
- **Browser Storage:** Uses the browser's `localStorage` to save item records so they can remain available when the page is reopened in the same browser.

## Technologies Used

- HTML5 — page structure and forms
- CSS3 — styling and layout (through `style.css`)
- JavaScript — form handling, searching, displaying, deleting, and saving item records
- Browser `localStorage` — local data storage

## Project Files

```text
College-Lost-and-Found/
├── index.html
├── style.css
└── script.js
```

- `index.html`: Contains the website structure, lost/found forms, search section, and item display area.
- `style.css`: Contains the website's styles and visual layout.
- `script.js`: Handles form actions, item creation, searching, displaying, deleting, and local storage.

## How to Run the Project

1. Download or clone this repository.
2. Keep `index.html`, `style.css`, and `script.js` in the same folder.
3. Open `index.html` in a web browser.
4. Choose **Report Lost Item** or **Report Found Item**.
5. Enter the item details and submit the form.
6. Use the search box to find items by name, or choose **Show All** to display all saved items.

## How Data Is Stored

The project saves item records in the browser's `localStorage` using the key `lostFoundItems`. This storage is local to the browser and device/profile being used. It does **not** create a shared online database, so records are not automatically visible to other users on different devices.

## Important Notes

- Keep all three project files in the same folder so the HTML page can load the CSS and JavaScript files.
- Item records are stored locally in the browser.
- Do not enter sensitive personal information into a public demo.

## Future Improvements

Possible future improvements include:
- Connecting the project to a shared database.
- Adding user authentication.
- Adding filters by lost/found status or date.
- Improving form validation and accessibility.

## Author

Add your name here.

## License

Add a license if you want others to reuse or modify this project.
# python-projects
My beginner Python projects and practice work

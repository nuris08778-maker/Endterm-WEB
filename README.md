# Aura Shop

Topic: Online Shop (clothes, gadgets, cosmetics)

## Group members

- Nursultan Nurislam
- Sarbasov Ayan
- Zhanassyl Omar

## Short description

Aura Shop is a multi-page website of an online store. Users can look at clothes, gadgets and cosmetics, search and filter products, compare and manage products in a table, register an account, send a contact form and view photos in a gallery. The midterm project (HTML, CSS, Bootstrap, responsive layout) is the base, and the endterm project adds interactivity with JavaScript and jQuery.

## Features

### Midterm features

- 6 pages: Home, Products, Compare, About, Contact, Register
- Navigation menu on every page
- Product cards and gallery
- Product comparison table
- Contact form
- Responsive layout for tablet and mobile

### Endterm features (JavaScript + jQuery)

1. **Form validation** (`register.html`, `contact.html`)
   - Required field checks for name, email, password and message
   - Email format check with a regular expression (RegEx)
   - Password strength indicator: weak, medium or strong (colored progress bar + text)
   - Password confirmation check (both fields must match)
   - Real-time feedback with Bootstrap valid/invalid states, messages and alerts
   - Form submission is blocked when validation fails
2. **Dynamic search and filter** (`products.html`)
   - Real-time search bar that filters products while the user types (`input` / `keyup` events)
   - Category buttons: All, Clothes, Gadgets, Cosmetics
   - Search and category filter work together, case-insensitive, without page reload
   - "No products found" message and a results counter
3. **Dynamic table with CRUD** (`compare.html`)
   - Create: "Add product" button opens a Bootstrap modal with a validated form
   - Read: all records are rendered dynamically in the table
   - Update: "Edit" button opens the modal with the current data
   - Delete: "Delete" button asks for confirmation before removing the item
   - Data is saved in the browser (localStorage), so it stays after page reload
4. **Image gallery with lightbox** (`about.html`)
   - Responsive image grid built with HTML, CSS and Bootstrap
   - Click on an image to open the lightbox with previous / next arrows
   - Keyboard support: left / right arrows and Esc, click on the background to close
   - Smooth jQuery transitions: `.fadeIn()` and `.fadeOut()`

## Technologies

- HTML5
- CSS3
- Bootstrap 5 (CSS and JS bundle)
- JavaScript (ES5/ES6)
- jQuery 3.7
- Google Fonts

## Project structure

```
index.html
products.html
compare.html
about.html
contact.html
register.html
css/style.css
js/script.js
README.md
```

## Individual contribution

## Individual contribution

- **Nursultan Nurislam**: Created the form validation on `register.html` and `contact.html`: required fields, email check with RegEx, password strength indicator, password confirmation and real-time Bootstrap feedback. Built the new Register page and added it to the navigation menu. Also wrote the README and merged all parts of the code into the main repository.
- **Sarbasov Ayan**: Created the dynamic search and category filter on `products.html`: real-time search with the `input` / `keyup` event, category buttons, combined search + filter logic, the "No products found" message and the results counter. Also built the image gallery on `about.html` with the lightbox, previous / next arrows, keyboard control and the jQuery `.fadeIn()` / `.fadeOut()` transitions.
- **Zhanassyl Omar**: Created the dynamic CRUD table on `compare.html`: rendering the products (Read), the Bootstrap modal form for adding (Create) and editing (Update), delete with confirmation (Delete), form validation in the modal and saving data in localStorage. Also tested the whole website on desktop and mobile and published it on GitHub Pages / Netlify.

## Website link


Student Registration System (DOM + LocalStorage):

Developed as a Learning Project for JavaScript, DOM Manipulation and Local Storage.

This project is a simple Student Registration System built using HTML, TailwindCSS, and JavaScript.
It allows users to add, edit, delete, and store student records. The data is retained using the browser's Local Storage.

Features:
Can add student details (Name, ID, Email, Phone Number).

Can edit existing student records.

Can delete student records.

Data is stored in LocalStorage so it persists even after refreshing or closing the browser.

Input validations in the form:

Student Name – accepts only letters and spaces.

Student ID – accepts only positive numbers, at least 10 digits.

Email – must follow standard email format.

Phone Number – accepts only numbers with at least 10 digits.

Technologies Used:

HTML5 – structure of the form and records display.

Tailwind CSS – for styling the UI.

JavaScript (DOM + LocalStorage) – for logic, functionality, validation, and data persistence.

Project Structure:
│── index.html Main HTML file with JavaScript logic
│── input.css Tailwind input file(source)
│── output.css Tailwind compiled output CSS file
│── package.json file that contains all the scripts and metadata
│── README.md Documentation

How It Works:

When the page loads, student data is retrieved from localStorage (if available) and displayed.

On clicking Submit button:

Input data is validated.

If valid data is entered, a student object {name, id, email, phone} is created.

If you click edit button and edits data, it updates the record.

If new, on clicking submit button, it pushes it into the students array.

Data is saved back into localStorage.

UI is refreshed by re-rendering all records.

On clicking delete button, the record is removed from the array and localStorage, and UI updates instantly.

On clicking edit button, the student’s data is loaded back into the form for updating.

How to Run:

Clone or download the repository.

Open index.html in a browser.

Command to build project is npm run build:css

Add student details using the form.

Refresh or reopen the page and data remains due to LocalStorage.

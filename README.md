# Project_intergrated.html
Adding Students:

    Users fill in the student name and ID in the "Add Student" form and submit it.
    The JavaScript checks if the student ID is unique, adds the student to the access list, and updates the display.

Removing Students:

    Users enter a student ID in the "Remove Student" form and submit it.
    The JavaScript searches for the ID in both lists, removes the student if found, and updates the display.

Displaying Lists:

    The displayLists function iterates over the access and deny lists, generating HTML content to display each student’s information.
    Students in the access list have an additional button to download a QR code containing their ID and name.
    Initial lists of students with access and those denied access are defined as arrays of objects.
A displayLists function dynamically updates the HTML content of the access and deny lists based on these arrays.
Event listeners on the "Add Student" and "Remove Student" forms handle form submissions:

    The "Add Student" form adds a new student to the access list if the ID is unique.
    The "Remove Student" form removes a student from either list based on the ID.

A downloadQRCode function generates a QR code for a student’s ID and name using the QRious library and triggers a download of the QR code image.

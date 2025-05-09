# Simple-Project
CRUD OPERATION(Create,Update,Delete,Read)
db.php is the main file used to connect to the Mysql database.

This file is included at the top of every other PHP file to access the database.

index.php is the homepage that reads and displays all records from the database.

It uses SELECT to fetch data and shows Edit/Delete links for each record.

create.php contains a form to add new data and uses an INSERT query to save it.

After submitting the form, it redirects back to index.php.

update.php loads a record based on the id passed via the URL.

It shows the current values in a form and updates the database using UPDATE.

delete.php deletes a record based on the id in the URL using a DELETE query.

After deletion, it also redirects to index.php.

Navigation between these files is done using hyperlinks with query parameters.

All database operations use the same $conn object from db.php.

This structure separates each function clearly into its file.

HTML forms are used for Create and Update actions.

The app runs smoothly with these connected files through shared database access.

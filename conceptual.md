### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?

PostgreSQL is an open source Relational Database Management System 

- What is the difference between SQL and PostgreSQL?

SQL is structured query language which makes querying language used by programs like PostgreSQL human readable due to PostgreSQL adhereing to SQL syntax guidelines

- In `psql`, how do you connect to a database?

psql 'database name here'

- What is the difference between `HAVING` and `WHERE`?

WHERE filters all rows based on a condition while HAVING filters a group or groups of rows based on a condition.

- What is the difference between an `INNER` and `OUTER` join?

INNER joins only return rows that match the specified consition form both tables while OUTER joins return all row from both tables.

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?

LEFT OUTER joins return all of the rows from the first table (left), combined with matching rows from the second table (right). RIGHT OUTER joins return the matching rows from the first table (left), combined with all the rows from the second table (right).

- What is an ORM? What do they do?

Object Relational Mapping tools help your databases interact and function with object oriented programming languages making working with both much simpler than having to write all the required code organically.

- What are some differences between making HTTP requests using AJAX and from the server side using a library like `requests`?

With client side http/ajax you can use communicate directly with the API without the use of a web framework like flask and is generally faster becuse of the direct communication. With server side requets the same-origin policy can prevent browser requests its easier for the server to store or process data and a password is required to access the API.

- What is CSRF? What is the purpose of the CSRF token? 

Cross-Site Request Forgery its' purpose is to validate form submissions to prevent unauthoried sites from submitting to its' respective url. 

- What is the purpose of `form.hidden_tag()`?

To hide the CSRF token field that gets submitted with each form submission.
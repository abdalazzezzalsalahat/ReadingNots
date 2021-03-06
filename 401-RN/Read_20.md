# Django

## Django : 
> **is a high-level Python web framework that enables rapid development of secure and maintainable websites.**

* *It can work with any client-side framework, and can deliver content in almost any format.*

> *Django provides a secure way to manage user accounts and passwords, avoiding common mistakes like putting session information in cookies where it is vulnerable (instead cookies just contain a key, and the actual data is stored in the database) or directly storing passwords rather than a password hash.*

## Scalable:

> *Each part of the architecture is independent of the others, and can hence be replaced or changed if needed.*

> *Django is "somewhat opinionated". It provides a set of components to handle most web development tasks and one (or two) preferred ways to use them. However, Django's decoupled architecture means that you can usually pick and choose from a number of different options, or add support for completely new ones if desired.*


* **A URL mapper is typically stored in a file named `urls.py`.**

1.  **`views.py`:**
> *Views are the heart of the web application, receiving HTTP requests from web clients and returning HTTP responses. In between, they marshall the other resources of the framework to access databases, render templates.*

**(generate response): The Django model provides a simple query API for searching the database.**

2. **`models.py`:**

>  *Django web applications manage and query data through Python objects referred to as models. Models define. the structure of stored data, including the field types and possibly also their maximum size, default values, selection list options, help text for documentation, label text for forms.*


> > > *Template systems allow you to specify the structure of an output document, using placeholders for data that will be filled in when a page is generated.*

## 1. What is `@login_required`?

`@login_required` is a Django decorator that allows only logged-in users to access a view. If the user is not logged in, they are redirected to the login page.

## 2. What is `@post_required`?

`@post_required` is used to allow a view to handle only `POST` requests. It is commonly used for actions like submitting forms or creating data.

## 3. How do you display variables in Django templates?

We use double curly braces `{{ }}` to display variables. For example, `{{ username }}` displays the value of the `username` variable.

## 4. What is template inheritance?

Template inheritance allows us to create a common base template and reuse it in other templates using `{% extends %}` and `{% block %}`.

## 5. What are the three parameters passed to the `render()` function in a view?

The three parameters are **request, template name, and context**. For example: `render(request, "home.html", {"name": "John"})`.

## 6. What is ORM?

ORM stands for **Object-Relational Mapping**. It allows us to interact with the database using Python classes and objects instead of writing SQL directly.

## 7. Why do we use `ALLOWED_HOSTS`?

`ALLOWED_HOSTS` specifies which domain names or IP addresses are allowed to access the Django application. It also helps protect the application from invalid Host header attacks.

## 8. What is callback hell, and what problems does it cause?

Callback hell happens when many callbacks are nested inside each other. It makes the code difficult to read, understand, and maintain.

## 9. Why is Django called a framework?

Django is called a framework because it provides ready-made tools and structure for building web applications, such as URLs, views, models, templates, and authentication.

## 10. What are the rules for writing a REST API?

A REST API should use proper HTTP methods, meaningful URLs, stateless requests, and suitable status codes. It should also usually exchange data in a format like JSON.

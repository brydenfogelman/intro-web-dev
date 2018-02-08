# Introduction to Web Development

A quick list of some important topics for those interested in starting web development. *Currently a work in progress and will be adding more *.

The best way to get started is to clone an already exsisting website (Twitter / Reddit / Blog / Facebook). Start with the Django polls app and slowly add to it. For example, update the UI to look like Reddit and then try and let the user upload new posts via Ajax (https://simpleisbetterthancomplex.com/tutorial/2016/08/29/how-to-work-with-ajax-request-with-django.html). During this you'll need to use to google to help you with whatever step your stuck on (ex. "How can I add images into HTML" or "How to use Django and Ajax").

To learn the syntax of any language I reccomend www.codecademy.com or https://www.codeschool.com/. I don't think anything past the very basic tutorials is useful. Working on your own project will require you to write your own code but use google to give you an idea of where to start.

## Languages/Frameworks

- HTML and CSS (https://developer.mozilla.org/en-US/docs/Web)
- Javscript
- Python
- Django
- React
- Bootstrap (https://getbootstrap.com/)
- Developer Tools (https://developers.google.com/web/tools/chrome-devtools/inspect-styles/)
- Git

## Concepts

Knowing some of the key concepts is half the battle so you know what you should be googling.

- CRUD (Create, Read, Update, Delete)
- RESTful API
- MVC (Model View Controller)
- Databases (Postgres)
- AJAX
- Forms
- Authentication

## HTML/CSS

This comes from experience and googling when you needs things. HTML and CSS is not hard to learn but its really easy to do badly. Look at how other people structure their code online and mirror that style. 

Use a framework like Bootstrap will save you hours and hours of development time as it comes prebuilt with a lot of useful CSS and HTML components (and a grid system!).

One of the most important aspects of HTML is the forms: https://developer.mozilla.org/en-US/docs/Learn/HTML/Forms/Your_first_HTML_form (also the mozzila developer website is a great resource for HTML, CSS. Forms allow the user to enter in data which will be added to the database (ex. User signup).

## Backend (Django/Python)

The Django documentation is a great start: https://www.djangoproject.com/start/. I would start with polls app and you should have a good handle on the basics of Django. 
https://docs.djangoproject.com/en/2.0/intro/tutorial01/. The documentation is very well written with great example so once you're familiar with Django take a quick glance at it so you're familair with some of the things you can do.

Checkout Django REST Framework.

## Frontend (Javascript)

List of important concepts / frameworks:
- Ajax
- Asynchronous (Deferred, Promises)
- jQuery
- React or Angular

AJAX is the big concept here, it allows you to load backend content without refreshing the page. All the big frameworks now (React, Angular) use this principal to make SPAs (single page web applications). In the past all websites used to be multi-page web applications meaning you would need to load a new page for each interaction.

https://en.wikipedia.org/wiki/Ajax_(programming)

Either you can use vanilla Javascript or jQuery, this is the OG way of doing things. Starting with Jquery is a good idea because its so easy to make 

https://www.w3schools.com/jquery/ajax_ajax.asp

Javascript is also asynchronous which means it does not execute all of its code line by line like Python. This leads=

https://www.sitepoint.com/introduction-jquery-deferred-objects/

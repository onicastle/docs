title: What is WSGI

# [WSGI](https://wsgi.readthedocs.io/en/latest/)
---

WSGI is the Web Server Gateway Interface. It is a specification that describes how a web server communicates with web applications, and how web applications can be chained together to process one request. WSGI is a Python standard described in detail in [PEP 3333](https://www.python.org/dev/peps/pep-3333/).

> What is WSGI

In a single sentence the answer is: *WSGI it is just an interface specification by which server and application communicate.*
This interface used by many popular frameworks like [Flask](/what-is/flask/) and [Django](/what-is/django/) is defined in the [PEP 3333](https://www.python.org/dev/peps/pep-3333) specification for both parties: server and WSGI application.

Python 2.5 and later comes with a WSGI server which will be used in this tutorial. In 2.4 and earlier it can be installed.

<br />

## WSGI Frameworks
---

A short-list with web frameworks with native WSGI support:

- [Flask](https://flask.palletsprojects.com/en/1.1.x/) - Flask is a microframework for Python based on Werkzeug, Jinja 2 and good intentions
- [Django](https://www.djangoproject.com/) - The web framework for perfectionists with deadlines.
- [Pyramid](http://www.pylonsproject.org/projects/pyramid/about) - Pyramid is a minimalist web framework aiming at composability and making developers paying only for what they use.
- [Falcon](http://www.pylonsproject.org/projects/pyramid/about) - Falcon is a high-performance Python framework for building cloud APIs

<br />

## Links & Resources
---

- [WSGI](https://wsgi.readthedocs.io/en/latest/)
- [An introduction to WSGI](http://ivory.idyll.org/articles/wsgi-intro/what-is-wsgi.html) by Titus Brown
- [Frameworks that run on WSGI](https://wsgi.readthedocs.io/en/latest/frameworks.html)

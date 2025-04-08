# FLASK-3
USING BLOCK CONTENT
In Flask, you can use template inheritance to keep your HTML clean and organized.

For example:

    You can create one main layout (called base.html)

    Then each page like home.html, about.html, etc., can extend that layout

    Inside these child pages, you use {% block content %} to fill in the page-specific stuff

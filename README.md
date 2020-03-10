# Automation
This project aims to teach you configuration management and automated deployment using an ansible.

It is a web-based survey application. Poll is a Python Flask web application that collects votes to push them into a Redis queue. The Java worker consumes the votes stored in the Redis queue, then pushes them into a PostgreSQL database. Finally, the web application Node.js Result retrieves the votes from the database and displays the result.

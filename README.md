# Automation
Epitech Project
This project aims to teach you configuration management and automated deployment using ansible.
The application you are working on during this project is a simple poll web application. Poll is a Python Flask web application that gathers the votes to push them into a Redis queue. The Java Worker consumes the votes stored in the Redis queue, then pushes it into a PostgreSQL database. Finally, the Node.js Result web application fetches the votes from the DB and displays the result.

# magasin-scp

## Description

Magasin SCP is a simple web app that allows Franco-Ouest students to access their stamps. Within the website, they can first create an account with their full name, school email address and a password. Later, they can log in to access the amount of stamps they have acquired during the year, and purchase rewards that they desire. Teachers on the other hand can login to access and manage their students stamps.

Our main technologies that we used were HTML, Bootstrap, Flask and SQLite. Our biggest difficulties were figuring out what technologies suited best for our needs, figuring out what features we wanted the website to have, and creating the authentication portion of the website. We do not plan to implement any new features in the nearby future, but rather, we hope to maintain the website as it gets used.

## How to use the website

1. Create an account with your first name, last name, school email address and password
2. Login to your account to view the amount of stamps you have
3. Purchase any rewards that you want based on your balance
4. Logout when you are finished

## Project configuration

NOTE: if you are using Docker, you can skip step 3 and 4 in favor of runnning `docker compose up` to test the web app in a Docker container.

1. Fork this project and git clone it to your machine
2. Move the repository to your preferred location
3. Create a python virtual environment and activate it
4. Install dependencies from the requirements.txt file
5. Make sure your Python formatter is set to `Black` and that `format on save` is turned on
6. Create a `.env` file inside the `magasinscp` package with the following variables and fill the values in
```
KEY=
MESSAGE_SENDER_EMAIL_ADDRESS=
MESSAGE_SENDER_PASSWORD=
STAFF_EMAIL_ADDRESS=
```
7. Add a git remote named `upstream` with the SSH link from the [main repository](https://github.com/FO-Informatique/magasin-scp)

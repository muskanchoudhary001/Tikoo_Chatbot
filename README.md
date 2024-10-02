 
# Tikoo Chatbot

Tikoo is a basic yet effective chatbot built with PHP, HTML, and CSS, supported by MySQL for database integration. It is designed to showcase simple chatbot functionalities and can be easily set up on a local server using XAMPP.
# Key Features

    Interactive Chat Interface: A clean and user-friendly interface for seamless user interaction.
    Chatbot Responses: Automated replies based on predefined data stored in a MySQL database.
    Database Integration: Efficient management of queries and responses through MySQL.
    Local Deployment: Easy to run on localhost using XAMPP, perfect for development and testing.

# Getting Started

To get Tikoo running on your local machine, follow these steps:
Prerequisites

    XAMPP (Apache & MySQL Server)

Installation Steps

    Clone the repository:

    bash

git clone https://github.com/muskanchoudhary001/Tikoo_Chatbot.git

Install and start XAMPP:

    Launch Apache and MySQL servers through the XAMPP control panel.

Set up the MySQL database:

    Navigate to phpMyAdmin.
    Create a new database named tikoo.
    Import the SQL schema located in the database/tikoo.sql file into your newly created database.

Move the project to the XAMPP htdocs directory:

bash

mv Tikoo_Chatbot /path_to_xampp/htdocs/

Open the chatbot in your web browser by visiting:

bash

    http://localhost/Tikoo_Chatbot/bot.php

# How to Use

    Start a conversation by typing a message in the chatbox.
    Hit the "SEND" button, and Tikoo will generate a response based on the query.
    The chatbot’s responses are fetched from the MySQL database.

# Contributing

If you'd like to contribute, feel free to fork the repository, make your changes, and submit a pull request. We appreciate all forms of contribution!
License

This project is licensed under the MIT License.
Credits

This project was developed as a simple demonstration of chatbot functionality using PHP and MySQL.

# Enjoy your chat with Tikoo! 🤖

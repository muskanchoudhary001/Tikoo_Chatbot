# Tikoo Chatbot

Tikoo is a simple chatbot project built using PHP, HTML, CSS for styling, and MySQL for database management. This project aims to demonstrate the basic functionality of a chatbot integrated with a database.

## Features

- User-friendly interface
- Chatbot functionality for answering user queries
- MySQL database integration for storing and retrieving data
- Easy to deploy on localhost using XAMPP

## Installation

To run Tikoo on your localhost, follow these steps:

1. Clone this repository to your local machine.
   ```
   git clone https://github.com/muskanchoudhary001/Tikoo_Chatbot.git
   ```

2. Install XAMPP on your system if you haven't already. You can download it from [here](https://www.apachefriends.org/index.html).

3. Start the Apache and MySQL servers using XAMPP control panel.

4. Import the database schema.
   - Open phpMyAdmin (usually accessible via http://localhost/phpmyadmin).
   - Create a new database named `tikoo`.
   - Import the `tikoo.sql` file located in the `database` directory of this project into the `tikoo` database.

5. Move the cloned `tikoo-chatbot` directory to your XAMPP `htdocs` directory.

6. Access Tikoo in your web browser by navigating to `http://http://localhost/chatbot/bot.php`.

## Usage

- Once you have accessed Tikoo in your web browser, you can start chatting with the chatbot.
- Type your query in the input field at the bottom of the chat interface and press ont the SEND button on the bot interface.
- Tikoo will process your query and provide a response based on the data stored in the database.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve Tikoo.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- This project was inspired by the need for a simple chatbot implementation using PHP and MySQL.
 
  
Happy chatting with Tikoo! 😁🤖

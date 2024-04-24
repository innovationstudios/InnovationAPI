# 🚀 InnovationAPI - Whatsapp Business Oficial

Este é um projeto API utilizando a lib oficial do WhatsApp Business V18.0, para envio de midia, template e mensagem definidas manualmente!

Overview
This repository contains a Node.js application designed for various purposes, including user authentication, server status monitoring, and message sending via different channels such as WhatsApp.

Dependencies
dotenv: Load environment variables from a .env file.
winston: Logging library for Node.js.
express: Web framework for Node.js.
node-fetch: HTTP client for making requests to external APIs.
multer: Middleware for handling multipart/form-data, primarily used for file uploads.
fs: File system module for Node.js.
bcrypt: Library for hashing passwords.
crypto: Cryptography module for Node.js, used for calculating SHA-256 hashes.
mysql2: MySQL client for Node.js.
cors: Middleware for enabling CORS in Express.
http: HTTP module in Node.js.
ws: WebSocket library for Node.js.
systeminformation: Library for retrieving system information.
jsonwebtoken: Library for generating and verifying JSON Web Tokens (JWT).
Endpoints
POST /auth/login: Endpoint for user authentication.
POST /auth/register: Endpoint for user registration.
GET /v2/status: Endpoint for retrieving server status.
POST /v2/send-media: Endpoint for sending messages with media.
POST /v2/send-message: Endpoint for sending text messages.
POST /v2/webhook: Endpoint for receiving messages from WhatsApp webhook.
Main Features
User Authentication: Allows users to authenticate in the application.
User Registration: Allows new users to register in the application.
Server Status Monitoring: Provides information about server status, including CPU, memory, disk, and temperature.
Message Sending with Media: Allows sending messages with media files, such as images.
Text Message Sending: Enables sending text messages to phone numbers.
WhatsApp Webhook: Receives messages sent to a WhatsApp number and processes them.
Usage and Configuration
To use the application:

Install dependencies with npm install.
Set environment variables in the .env file.
Run the application with npm start.
Required environment variables include MySQL database credentials, HTTP server settings, Facebook API URL, Facebook API access token, and other configuration details.

Contribution
Contributions are welcome! Feel free to fork this repository, make your changes, and submit a pull request.

License
This project is licensed under the MIT License. Feel free to use and modify this code for your purposes.

Acknowledgements
Thanks to all the contributors who have helped improve this project.
Special thanks to the authors of the libraries and dependencies used in this project.
Contact
For any questions or inquiries, please contact project@example.com.

References
Express.js Documentations
MySQL2 Documentation
Winston Documentation
Node-fetch Documentation
Multer Documentation
Support
If you find any issues or have suggestions for improvement, please open an issue on GitHub.

This README provides an overview of the application, its features, and usage instructions. Feel free to customize it according to your project's needs.

### Contribuição

**Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue para relatar problemas ou propor melhorias.
**Segue meu pix: victorgd199@hotmail.com Qualquer valor é bem vindo!

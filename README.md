# Node.js Chat and IM Project

## Synopsis
This project aims to create a chat application for software engineers to communicate with each other in real-time. The application will allow users to exchange code snippets, links, and ideas securely. It will support group chats and provide the ability to maintain chat history for a specified duration.

## Features
- Real-time communication using Node.js and Socket.IO
- User authentication for secure access
- Group chat functionality for collaborative discussions
- Message encryption using the crypto-js library
- Database integration (e.g., MongoDB) to store chat history
- Configurable chat history duration (default: 7 days)
- Simple front-end interface for user interaction

## Technologies Used
- Node.js
- TypeScript
- Python (for future enhancements)
- Express.js (for server setup)
- Socket.IO (for real-time communication)
- MongoDB (for chat history storage)
- crypto-js (for message encryption)

## Getting Started
1. Clone the repository.
2. Install the required dependencies using npm.
3. Set up the Node.js server with Express.js.
4. Implement user authentication and group chat functionality.
5. Integrate a database (e.g., MongoDB) for chat history storage.
6. Implement message encryption using the crypto-js library.
7. Create a simple front-end interface using HTML, CSS, and JavaScript.

## Usage
1. Run the Node.js server.
2. Access the chat application through a web browser.
3. Register or log in to start using the chat features.
4. Create or join chat groups to communicate with other users.
5. Exchange code snippets, links, and ideas securely.
6. Chat history will be stored in the database for the specified duration.
7. Customize the chat history duration or wipe the history as needed.

## Future Enhancements
- File attachments support
- Enhanced security measures
- Additional integrations with other programming languages

## License
This project is licensed under the [MIT License](LICENSE).
## Implementation

To implement the chat application, follow these steps:

1. Set up a Node.js server with Express.js to handle incoming requests.
2. Use Socket.IO for real-time communication between the server and clients.
3. Implement user authentication and group chat functionality.
4. Use a database (e.g., MongoDB) to store chat history.
5. Implement message encryption using a library like crypto-js.
6. Create a simple front-end interface using HTML, CSS, and JavaScript.

### Server Setup

Connecting with MongoDB for VS Code
1. Install MongoDB for VS Code.
In VS Code, open "Extensions" in the left navigation and search for "MongoDB for VS Code." Select the extension and click install.
2. In VS Code, open the Command Palette.
Click on "View" and open "Command Palette."
Search "MongoDB: Connect" on the Command Palette and click on "Connect with Connection String."
3. Connect to your MongoDB deployment.
Paste your connection string into the Command Palette.

Show Password
mongodb+srv://chattynodeapp:WYSYZ45IUD48utav@cluster0.scb2kdp.mongodb.net/

The password for chattynodeapp is included in the connection string for your first time setup. This password will not be available again after exiting this connect flow.
4. Click “Create New Playground” in MongoDB for VS Code to get started.
Learn more about Playgrounds 
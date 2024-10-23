# Java Chat Application

This is a simple Java-based chat application that allows **two users** to connect and chat with each other over a local network. The application consists of two components:

- `Server.java`: The server-side component that manages client connections.
- `Client.java`: The client-side component that enables individual users to connect to the server and communicate.

## Getting Started

### Prerequisites

- Java JDK 8 or higher
- Any IDE (e.g., IntelliJ, Eclipse) or terminal with Java configured
- Local network setup (for client-server communication)

### Running the Application

1. **Clone the repository**:
   ```bash
   git clone https://github.com/veera21030/JavaChatApp.git
   cd JavaChatApp
2. **Run the Server**:

   First, you need to run the Server.java file to start the chat server. This can be done in an IDE or via the terminal.
   ```bash
   javac Server.java
   java Server

   The server will automatically fetch your local IP address and start listening for client connections.

3. **Run the Client**:

   After the server is running, you can run the Client.java file to connect a client to the server.
   ```bash	
   javac Client.java
   java Client

   By default, the client will attempt to connect to the server using the local IP. The application allows two users to connect and chat at the same time.

##Features

     Automatic local IP detection
     Two users can connect to the server and chat simultaneously
     Simple text-based communication

##Future Enhancements

     Add support for multiple users to connect to the chat
     Add encryption for secure communication
     Implement a GUI for easier usage
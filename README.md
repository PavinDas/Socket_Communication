# Client-Server Communication Using Python Sockets

This project demonstrates a simple client-server communication model using Python's `socket` module. The server listens for connections and echoes back messages sent by the client. It's a minimalistic example of TCP-based communication.

## Features
- Bi-directional communication using TCP.
- A server that handles one client at a time.
- Echo functionality for the client-server communication.

---

## Getting Started

### Prerequisites
Make sure you have Python 3 installed on your system. You can check your Python version with:
```bash
python3 --version
```
### Installation
Clone this repository:
```bash
git clone https://github.com/PavinDas/Socket_Communication.git
```
Navigate to the project directory:
```bash
cd Socket_Communication
```
## Usage
### Running the Server
Start the server by running server.py script:
```bash
python3 server.py
```
The server will start listening for connections on 127.0.0.1:65432
### Running the Client
In another terminal, run the client.py script:
```bash
python3 client.py
```
The client will connect to the server at 127.0.0.1:65432
### Interacting
- Enter messages in the client terminal.
- The server will echo the messages back to the client.
- To exit the client, type ```exit```

## Example Output
### Server terminal
```
Server started on 127.0.0.1:65432, waiting for a connection...
Connected by ('127.0.0.1', 65432)
Received: Hello, Server!
Received: How are you?
Connection closed by client.
```
### Client terminal
```
Connected to server at 127.0.0.1:65432
Enter a message (type 'exit' to quit): Hello, Server!
Received from server: Hello, Server!
Enter a message (type 'exit' to quit): How are you?
Received from server: How are you?
Enter a message (type 'exit' to quit): exit
Closing connection...
```
## 🛡️ Ownership

This project is owned by PavinDas


# Java Single Threaded Socket Server and Client

This project demonstrates a basic **single-threaded server and client communication** using Java Sockets.

- The server listens on port `8010`.
- When a client connects, it accepts the connection and responds with a greeting message.
- The client sends a message to the server and displays the response.
- Built using Java's `Socket`, `ServerSocket`, `BufferedReader`, and `PrintWriter`.

---

## 🧪 How to Run

### ➤ Step 1: Compile both files
```bash
javac Server.java
javac Client.java
```

### ➤ Step 2: Run the Server
```bash
java Server
```

### ➤ Step 3: Run the Client (in a new terminal or tab)
```bash
java Client
```

---

## 🔍 Sample Output

### Server Console
```
Server is listening on port: 8010
Connection accepted from client: /127.0.0.1:XXXXX
```

### Client Console
```
Response from the socket is: Hello from the server
```

---

## 👨‍💻 Author

Ashish Dubey

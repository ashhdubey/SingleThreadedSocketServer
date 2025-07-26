# Java Socket Programming – Single Threaded Server & Client

A simple Java application demonstrating socket communication between a server and a client using a single-threaded approach.

---

## 📌 Overview

- **Server** listens on port `8010`.
- Accepts a single client connection at a time.
- **Client** connects to the server and exchanges a basic message.

---

## 🛠️ Technologies Used

- Java SE
- Socket Programming (`java.net`)
- Input/Output Streams

---

## 🚀 How to Run

### 1. Compile the Code
```bash
javac Server.java
javac Client.java
```

### 2. Start the Server
```bash
java Server
```

### 3. Run the Client (in a new terminal)
```bash
java Client
```

---

## 🖥️ Example Output

### Server
```
Server is listening on port: 8010
Connection accepted from client: /127.0.0.1:XXXXX
```

### Client
```
Response from the socket is: Hello from the server
```

---

## 👤 Author

**Ashish Dubey**

---

## 📂 License

This project is open source and available under the [MIT License](LICENSE).


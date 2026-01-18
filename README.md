# Java Socket Chat Application

This is a simple client–server chat application built using **Java Socket programming** and **Swing**.  
The project demonstrates real-time communication between a client and a server over a TCP connection.

---

## Description

The application consists of two parts:
- **Server**: Listens for incoming connections and receives/sends messages.
- **Client**: Connects to the server and allows users to chat in real time.

Both sides use a basic Swing-based UI to display messages along with timestamps.

This project was built to understand core Java concepts such as socket programming, client–server architecture, and desktop UI development.

---

## Technologies Used

- Java
- Socket Programming (TCP)
- Swing (AWT & Swing components)
- DataInputStream & DataOutputStream

---

## Features

- Real-time text messaging
- Client–server communication
- Simple chat interface
- Message timestamps
- Scrollable chat window

---

## How to Run

1. Compile the files:
```bash
javac Client.java
javac Server.java
````

2. Run the server first:

```bash
java chatting.application.Server
```

3. Run the client:

```bash
java chatting.application.Client
```

Server runs on:

```
127.0.0.1 : 6001
```

---

## Purpose

This project is intended for learning **Java networking fundamentals** and understanding how real-time communication works using sockets.

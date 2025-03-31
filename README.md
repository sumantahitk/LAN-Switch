# LAN-Switch

# Socket Server and Client

This project demonstrates a basic **socket programming** setup in C using **TCP/IP** on Windows. The server listens for incoming client connections, and the client communicates with the server.

## Compilation and Execution Guide

### 1️⃣ Compile and Run the Server and Client

To compile and run the **server** and **client** programs, use the following commands in the terminal:

#### **For the Server:**

```bash
gcc -o server sock_srvr.c -lws2_32   # Compile the server
./server                             # Run the server (Linux/macOS)
server.exe                           # Run the server (Windows - Command Prompt)
```
#### **For the Client:**

```bash
gcc -o client sock_clnt.c -lws2_32   # Compile the client
./client 127.0.0.1(or any connected IP) # Run the client (Linux/macOS)
client.exe                           # Run the client (Windows - Command Prompt)
```

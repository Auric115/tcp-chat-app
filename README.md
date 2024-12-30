# Rust Chat App

A simple terminal-based chat application written in Rust using TCP sockets. It includes both a server and a client program for communication.

## Description

This project demonstrates a basic implementation of a chat server and client using Rust's `std::net` and concurrency primitives. The server can handle multiple clients and broadcast messages to all connected clients.

[Documentation](https://doc.rust-lang.org/)

---

## Features

- Multi-client support on the server.
- Concurrent message handling using threads.
    - Non-blocking sockets for efficient communication.
- Minimal terminal-based interface.

---

## How to Run

Follow the instructions below to set up and run the chat application.

### Requirements

- [Rust](https://www.rust-lang.org/tools/install) (Ensure Rust and Cargo are installed)
- Basic understanding of terminal commands.

### Instructions

1. Clone the repository:
   ```bash
   git clone <repo-url>
   cd <repo-name>
   ```

2. Run the server:
   ```bash
   cargo run --bin server
   ```

3. Open a new terminal and run the client:
   ```bash
   cargo run --bin client
   ```

4. Repeat step 3 to connect multiple clients.


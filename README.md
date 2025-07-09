 Real-time Multi-User Chat (Socket & Threading)

A foundational real-time chat application demonstrating direct network communication using Python's socket module and concurrent client handling via threading. It features a server that broadcasts messages, supports custom nicknames, and includes basic moderation commands.

 Features

- Instant message exchange between multiple clients.
- Server handles concurrent connections.
- Clients use unique nicknames.
- Messages are broadcast to all participants.
- Basic admin commands (e.g., /kick).

 Technologies

- Python 3.x  
- `socket` module (Network communication)  
- `threading` module (Concurrency)

 Getting Started

1. Clone the repository (ensure `server.py` and `client.py` are present).
2.  Create and activate a virtual environment:
   ```bash
   python -m venv venv
   venv\Scripts\activate  # On Windows
   source venv/bin/activate  # On macOS/Linux

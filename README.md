# 23071A3225-OS-10
The chat_server_unix.cpp is a local server using Unix domain sockets (AF_UNIX) for fast inter-process communication (IPC), while chat_client_unix.cpp connects to this server to exchange messages locally. On the other hand, chat_server_tcp.cpp is a TCP-based server (AF_INET) that listens on port 8080 for connections from multiple clients over a network, and chat_client_tcp.cpp connects to this server to enable remote communication. The key difference is that Unix domain sockets are used for local communication, offering faster performance, whereas TCP sockets allow communication over a network, enabling remote connections.




# Multithreaded-File-Transfer-using-TCP-Socket
A  multithreaded file transfer client-server program build using a python programming language. The server has the capability to handle multiple clients concurrently at the same by using threading. The server assigns each client a thread to handle working for that client.

# FUNCTIONS
* LIST :List all the files from the server.
* UPLOAD:   Upload a file to the  server.
* DELETE :   Delete a file from the server.
* LOGOUT:   Disconnect from the server.
* HELP:   List all the commands.


# Overview
The server program can handle an arbitrary number of concurrent connections and file exchanges, only limited by system configuration or memory. The server is started without any parameters and creates a TCP socket at an OS-assigned port. It prints out the assigned port number and stores it in a local file port, which is used when starting clients. The server listens on its main socket and accepts client connections as they arrive. Clients perform an upload or download operation, or instruct the server to terminate.

# Architecture

![image](https://user-images.githubusercontent.com/66979717/145279246-65c8d299-9aae-431d-8fa6-14f231d66f3a.png)

@all-contributors please add @prabhat187 for coding, design



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

# Contributers
<table>
  <tr>
   <td align="center"><img src="https://avatars.githubusercontent.com/u/66979717?v=4" width="200px;" height="200px;" alt=""/><br /><sub><b>Kireeti Nittala</b></sub></a><br />
  <br/>
   <p align="center">
   <a href="https://github.com/Kireeti2001" alt="Github">
     <img src="http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width = "30">
  </a>
  </p>
</td>
<td align="center"><img src="https://user-images.githubusercontent.com/51742771/144631900-5f912e5d-ba9c-477e-bbbd-edd9ce246c42.jpeg" width="200px;" height="200px;" alt=""/><br /><sub><b>Prabhat Addanki</b></sub></a><br />
  <br/>
   <p align="center">
   <a href="https://github.com/prabhat187" alt="Github">
     <img src="http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width = "30">
  </a>
  </p>
</td>
   <td align="center"><img src="https://avatars.githubusercontent.com/u/78893155?v=4" width="200px;" height="200px;"  alt=""/><br/><sub><b>Haswanth Kolanuvada
</b></sub></a><br />
   <br/>
   <p align="center">
   <a href="https://github.com/Haswanth2002" alt="Github">
     <img src="http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width = "30">
  </a>
  </p>
</td>
   <td align="center"><img src="https://avatars.githubusercontent.com/u/90751356?v=4" width="200px"; height="200px;" alt=""/><br /><sub><b>Pavan Kuchupudi</b></sub></a><br />
   <br/>
   <p align="center">
   <a href="https://github.com/PavanKuchipudi" alt="Github">
     <img src="http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width = "30">
  </a>
  </p>
</td>
<td align="center"><img src="https://avatars.githubusercontent.com/u/85001085?v=4" width="200px;" height="200px;" alt=""/><br /><sub><b>KIRAN MULLAPUDI</b></sub></a><br />
  <br/>
   <p align="center">
   <a href="https://github.com/kiran-alt" alt="Github">
     <img src="http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width = "20">
  </a>
  </p>
</td>
    </tr>
    </table>

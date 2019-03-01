
# Project 2: MultiThreaded FTP Client and Server(Distributed Computing Systems)

## a)Project Group Members
1) Bhavsar Radhika (#811648055)
2) Mahajan Jidhnyasa(#811259368)

## b) Compilation and Execution Instruction
The project is to introduce to design issues involved in multi-threaded servers. This project, is extend of first project to make both the client and server multithreaded. The client will be able to handle multiple commands (from same user) simultaneously and server should be able to handle multiple commands from multiple clients. The client and server will support the same set of commands as indicated in project 1 (get, put, delete, ls, cd, mkdir, pwd, quit). In addition, they will support one more command called “terminate”, which is used for terminating a long-running command (e.g., get and put on large files) from the same client. The port for normal commands are referred to as “nport” and the terminate port is referred to as “tport”.

Server Compilation and Execution (on terminal)<br >
>javac myftpserver.java<br >
>java myftpserver (specify nport tport)

Client Compilation and Execution (on terminal)<br >
>javac myftp.java<br >
>java myftp (specify machinename and server nport tport)

### References
Javadoc : https://docs.oracle.com/javase/10/

### “This project was done in its entirety by  Bhavsar Radhika and Mahajan Jidhnyasa. We hereby state that we have not received unauthorized help of any form.”



# Node.js

### <mark style="color:red;">What is Node.js?</mark>

* Node.js is an open-source server environment
* Node.js is free
* Node.js runs on various platforms (Windows, Linux, Unix, Mac OS X, etc.)
* Node.js uses JavaScript on the server

### <mark style="color:red;">Why Node.js?</mark>

**Node.js uses asynchronous programming!**

| How Node.js handles a file request                                                               | How PHP or ASP handles a file request                 |
| ------------------------------------------------------------------------------------------------ | ----------------------------------------------------- |
| Sends the task to the computer's file system.                                                    | Sends the task to the computer's file system.         |
| Ready to handle the next request.                                                                | Waits while the file system opens and reads the file. |
| When the file system has opened and read the file, the server returns the content to the client. | Returns the content to the client.                    |
|                                                                                                  | Ready to handle the next request.                     |

Node.js runs single-threaded, non-blocking, asynchronous programming, which is very memory efficient.

### <mark style="color:red;">What Can Node.js Do?</mark>

* Node.js can generate dynamic page content
* Node.js can create, open, read, write, delete, and close files on the server
* Node.js can collect form data
* Node.js can add, delete, and modify data in your database

### <mark style="color:red;">What is a Node.js File?</mark>

* Node.js files contain tasks that will be executed on certain events
* A typical event is someone trying to access a port on the server
* Node.js files must be initiated on the server before having any effect
* Node.js files have extension ".js"

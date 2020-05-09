# ThreadedObjectClientServerMessenger
a terminal based messenger that sends objects to other clients connected to the server

# To compile with javac
copy all files to a directory called ThreadedObjectClientServerMessenger
navigate one directory above and run   $ javac ThreadedObjectClientServerMessenger/*.java

# To run the server 
navigate one directory above ThreadedObjectClientServerMessenger
and call                               $ java ThreadedObjectClientServerMessenger/ObjectServer
** The server runs on tcp port 5000 **

# To run the client(s)
in a diffrent terminal navigate one directory above ThreadedObjectClientServerMessenger
and call                               $ java ThreadedObjectClientServerMessenger/ObjectClient <tcp> <ip>
for example                            $ java ThreadedObjectClientServerMessenger/ObjectClient localhost 5000
will connect to the server locally on ip address: 127.0.0.1   tcp port: 5000
(open a second terminal and open a second client to send messages between clients);
pass the same arguments as ip/tcp of the server.
  
# Terminal commands
simply send messages by typing to the terminal and pressing enter, the server will send messages to all other clients.
to close the server/client(s) from
ther terminal type                    $ .close 




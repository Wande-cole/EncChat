# EncChat
Encrypted messenger using sockets and AES
EncChat is written in JAVA and uses sockets as the basis for communication.

The application requires that all clients are on the same network, and the server application is started before the clients can communicate.
Users can login (check account details in data.xml) --you can add more users here.
Authenticated users can then send messages
Messages are encrypted using the key in the field provided (will be unencrypted if left blank).
The key provided by sender has to be the same as receiver to decrypt message

## How it Runs

![3client](1.png)

The way to run this application is to have atleast two terminals open one for the server and the second for the client. To run it the server must be ran first then any reasonable amount of clients. As the server runs and clients begin to start up they will be connected and it will be shown in the server terminal showing which clients connected. Once all connections are established clients can send messages to the server and the server will get the message and resend it to the other clients broadcasting it. Each select loop within each client will then output it in their terminals.
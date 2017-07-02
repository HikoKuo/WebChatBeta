Requirements : 
1. This chat application needs a Java-based server for SocketServer.
2. Install MQ Server (ex. ActiveMQ , RabbitMQ, IBM MQ...etc) for Messaging implementation.
3. This chat application can be run at WebBrowser, Android, iOS, Windows Phone because of HTML5 technology.
4. The chating messages refresh when two users are both online.


Algorithm : 
1. Chat client logins and send the message to socketServer for registation and connect to MQ Server by MQTT protocol.
2. After logon, socketServer returns the user list for online chating.
3. Sending messages to each one by MQTT protocol which could send bigger and more secure data.

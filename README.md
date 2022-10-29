• Frontend Technologies Used:

react: Used react and react-router to build frontend home and editor pages
react avatar: Generates avatars based on user information
react dom: Provides DOM specific methods that can be used at the top level of a web app
react hot toast: To create notifications
uuid: To create unique paths for multiple editors

• Backend Technologies Used:

express: For building server
socket.io: Enables low-latency, bidirectional and event-based communication between a client and a server

• Working

Main motive to use socket.io is its ability to fire on asynchronous events. The way it operates is that it listens to asynchronous messages being sent, and on receiving one, triggers a function that handles the rest. The main code here, was just to detect when a character is typed in, then send the text over the socket stream. The server socket having a message event registered sends the text stream over to all connected sockets. Then, all users registered the message event, will get the text stream from the server and set the textarea with the text stream.
  
  

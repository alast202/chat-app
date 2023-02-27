## chat-app using ReactJS and NodeJS

<p>To have a chat between two people they need to be inside the same room, each room has a specific id. User can choose their room name and another user 
must use the same room name to join.</p>
<p>When a new message is sent, the screen auto scrolls to view the latest message.</p> 

## Things I learned from the project.

<p>Socket.io works with events. So you commit an event and detect(listen) for the event to happen. 
I used the connection event to see if someone has connected to the socket.io server, which is (io.on).
Then have an action as a callback function- for mine i did  console.log(socket.id); </p>




https://user-images.githubusercontent.com/81660066/221645169-ba330b18-4690-43ae-b1b4-c1f4a5a4c7c2.mp4


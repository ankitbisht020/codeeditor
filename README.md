
# Real-Time Collaborative Code Editor

**Overview**
-This project is a Real-Time Code Editor that allows multiple users to collaborate on writing and editing code simultaneously. Users can create unique rooms, share their room code with friends, and see live updates in the editor as others type. The app uses WebSockets to establish a persistent live connection between users, ensuring real-time collaboration across different clients.

## Features ✨


- Create Rooms: Users can create unique rooms by entering a username, which generates a unique room code.
- Join Rooms: Friends can join an existing room using the room code shared by the creator.
- Real-Time Collaboration: All users in the same room can see real-time changes in the code editor.
- Live Synchronization: Changes made by one user are instantly reflected in the editors of all users in the same room.
- WebSocket Communication: The app uses WebSockets for bi-directional communication, enabling live updates across all users.

## Tech Stack 🛠️

**Client:** React

**Server:** Node, Express with WebSocket for real time communication 



## Installation & Setup 🖥️

To get started with the project locally:

**1.** Clone the Repository:

```bash
 git clone https://github.com/yourusername/link-shortener.git

```
**2.** Install Dependencies:

```bash
cd link-shortener
npm install

```
**3.** Start the Application:

```bash
 npm start

```

The app will be available at http://localhost:3000.

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`PORT=3000`


## Hoe to Use 📄

**1. Create a Room 🏠**

- Go to the website and enter your username.
- Click the "Create Room" button.
- A unique room code will be generated for you.

**2. Share the Room Code:**
- Share the room code with your friends so they can join your room.

**3. Join the Room**
- Friends can enter the room code and their username to join your room.

**4. Collaborate:**
- Once in the room, all users can type in the code editor and see real-time updates as others make changes.
- All changes are instantly synchronized using WebSocket, ensuring a smooth collaborative experience.

  
## WebSocket Communication 

The app relies on WebSocket for live communication. Here’s an outline of the events handled:

**Connection Established:**When a user joins a room, a WebSocket connection is created, and the user is added to the room.
**Real-Time Code Updates:** Every change in the editor (like typing, deleting) is broadcasted to other users in the same room through WebSocket events.
**Room Management:**WebSocket events manage creating and joining rooms and tracking users in each room.

## Future Enhancements

- User Authentication: Adding user authentication for private rooms.
- Chat Integration: Adding a chat feature so users can communicate while coding.
- Cloud data Saving: User can save there code on cloud.

## Contact

If you have any questions or suggestions, feel free to reach out:

**Email:** ankitbisht9837@gmail.com

**LinkedIn:** https://www.linkedin.com/in/ankitb-webd9905/

**GitHub:** https://github.com/ankitbisht020
 
 
 
***Enjoy using the Link Shortener! 😊***

Feel free to modify and add specific details such as live URLs, additional steps, or contribution guidelines based on your project's needs!

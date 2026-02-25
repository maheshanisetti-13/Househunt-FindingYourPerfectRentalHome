# Data Flow Diagram (DFD)

The Data Flow Diagram illustrates how data moves through the House Hunt system.

## Data Flow Description

1. The user interacts with the frontend interface developed using React.js.
2. User requests such as login, property search, or property details are sent to
   the backend server.
3. The backend server, developed using Node.js and Express.js, processes the request.
4. The server communicates with the MongoDB database to fetch or store data.
5. The processed data is sent back to the frontend.
6. The frontend dynamically displays the response to the user.

## Overall Data Flow

User → React Frontend → Node.js & Express Backend → MongoDB Database  
→ Backend → Frontend → User

This structured data flow ensures secure, real-time, and accurate information
delivery.

# Chat Application

A real-time chat application that allows users to create and join chat rooms, send and receive messages instantly, and persist conversations.

## Features

- **Room Management:** Users can create a new room with a unique room ID and join existing rooms.
- **Persistent Messaging:** All messages are stored in MongoDB, allowing users to view past conversations.
- **Real-Time Communication:** Utilize WebSockets for instant message delivery across all users in a room.

## Functional Requirements

### 1. Create Room
- Users can create a new room by providing a unique name or ID.
- The system validates the uniqueness of the room ID.

### 2. Join Room
- Users join an existing room by entering its room ID.
- Upon successful validation, users can view historical messages and chat in real-time.
- If the room ID is invalid, an error message is displayed.

### 3. Messaging
- Users send and receive messages in real-time.
- Messages are stored in MongoDB under the corresponding room.

### 4. Real-Time Communication
- WebSockets are used to ensure immediate message delivery to all users within a room.

## Non-functional Requirements

### 1. Scalability
- Supports multiple rooms and concurrent users.
- Efficient MongoDB schema design for managing large volumes of chat data.

### 2. Performance
- Real-time message delivery with minimal latency.
- Optimized REST API endpoints for fast and efficient data handling.

### 3. User-Friendly Interface
- Clean, responsive design built with **React** and **TailwindCSS**.

## Tech Stack

### Backend:
- **Java**
- **Spring Boot**
- **REST APIs**
- **WebSocket**
- **MongoDB**

### Frontend:
- **React**
- **TailwindCSS**


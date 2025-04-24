# DevArena

DevArena is a cutting-edge real-time coding competition platform built with a modern microservices architecture. The platform's core strength lies in its sophisticated real-time communication system, combining Socket.IO for client-server interactions and gRPC streaming for inter-service communication.
## Demo


https://github.com/user-attachments/assets/abb30f8f-e7e6-4a28-88fd-783f0b91898d


## Core Architecture

### Real-time Microservices Architecture

The platform is built on a robust microservices architecture with three main services:

1. **Main Service**

   - Handles user authentication and profile management
   - Manages contest creation and configuration
   - Integrates with multiple OAuth providers (Google, GitHub, Discord)


2. **Compile Service**
   - Code compilation and execution
   - Real-time code submission processing
   - gRPC streaming for continuous output/error feedback
   - Resource usage monitoring

### Real-time Communication Stack

#### Client-Server Communication (Socket.IO)

- Real-time contest updates
- Live leaderboard synchronization
- Instant code submission feedback
- Real-time chat and notifications
- Bi-directional communication for contest state management

#### Inter-Service Communication (gRPC Streaming)

- Continuous code compilation feedback
- Real-time resource usage monitoring
- Streamed test case execution results
- Performance metrics streaming
- Service health monitoring

## Technology Stack

### Frontend

- Next.js 15 with React 19
- TypeScript for type safety
- Socket.IO client for real-time features
- Monaco Editor for code editing
- TailwindCSS for styling
- Redux for state management

### Backend

- NestJS microservices
- MongoDB with Mongoose
- Socket.IO server
- gRPC with streaming support
- JWT authentication

## Key Features

### Real-time Contest Experience

- Live code submission and feedback
- Real-time leaderboard updates
- Instant contest state synchronization
- Live chat and notifications
- Continuous compilation feedback

### Advanced Code Execution

- Real-time code compilation
- Streamed execution results
- Resource usage monitoring
- Multiple language support
- Test case execution streaming

### User Experience

- Real-time contest updates
- Live coding environment
- Instant feedback on submissions
- Collaborative features
- Performance analytics

## Technical Highlights

### Socket.IO Integration

- Bi-directional real-time communication
- Room-based contest management
- Efficient event-based updates
- Automatic reconnection handling
- Scalable WebSocket implementation

### gRPC Streaming

- Continuous data streaming
- Efficient inter-service communication
- Low-latency code execution feedback
- Resource-efficient streaming
- Bidirectional streaming support


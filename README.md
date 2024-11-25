# ZugChess

**Status**: Under Development (No releases made yet)

ZugChess is an online platform designed for playing chess games. This project serves as my Bachelor Thesis at [University Name], majoring in [Major Name].

## Technology Stack

ZugChess is built using the following technologies:

- **Frontend**: Next.js with TypeScript
- **Backend**: Go
- **Real-time Communication**: WebSockets

**Reasons for Choosing This Stack**:

- **Next.js with TypeScript:** Next.js offers a robust framework for server-rendered React applications, enhancing performance and SEO. TypeScript adds static typing, improving code quality and maintainability.
- **Go:** Known for its simplicity and performance, Go is well-suited for building scalable backend services. Its concurrency model is particularly advantageous for handling multiple simultaneous connections, which is essential for real-time applications like ZugChess.
- **WebSockets:** To facilitate real-time communication between players, WebSockets provide a full-duplex communication channel over a single, long-lived connection, ensuring a seamless gaming experience.
- **PostgreSQL:** A powerful, open-source relational database system, PostgreSQL provides robust data integrity, scalability, and support for complex queries, making it ideal for managing user data and game states.
- **Redis:** An in-memory data structure store, Redis is used for caching and real-time message brokering, facilitating quick data retrieval and efficient handling of real-time game updates.
- **Docker:** By containerizing the application, Docker ensures consistent environments across development, testing, and production. This approach simplifies deployment and scaling, especially when hosting on a Virtual Private Server (VPS).

Also, ZugChess utilizes a monorepo architecture, where both the frontend and backend codebases reside within a single repository.

## Future Plans

The primary goal of ZugChess is to enable users to play chess online with the following features:

- **Game Creation:** Users can create new chess hers to join.
- **Join Game:** Players can join existing games using a unique game identifier.
- **Real-time Gameplay:** Utilizing WebSockets, the platform will provide real-time updates, ensuring a smooth and responsive gaming experience.

In future iterations, the platform aims to introduce an AI opponent(chess bot), allowing users to play against a computer-controlled player. This feature will involve developing a chess engine capable of evaluating board positions and making strategic moves.

## Development Updates

I will regularly document the development process and share insights on my blog: https://blog.starigeri.hu

---

_Note: This project is currently in development, and no official releases have been made yet._

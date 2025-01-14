# Talkify Frontend

## Overview

The **Talkify Frontend** is the user interface of the Talkify real-time chat system. Built with **Next.js** (a React framework), it provides an interactive and seamless experience for users to communicate and manage their chats. This repository is part of the multi-repository setup for Talkify.

## Features

- Responsive design for chat functionality.
- Real-time messaging via integration with the backend.
- User authentication and session management.
- Dynamic chat list and message views with server-side rendering (SSR) and static site generation (SSG).

## Tech Stack

- **Next.js**: React-based framework for building modern web applications with SSR and SSG capabilities.
- **Axios**: For making API requests to the backend.
- **CSS/SCSS**: For styling the application.
- **WebSockets/SignalR**: For real-time updates.

## Prerequisites

- **Node.js**: Ensure Node.js is installed on your machine.
- **Package Manager**: Use npm or yarn to manage dependencies.

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/tassan/talkify-frontend.git
cd talkify-frontend
```

### Install Dependencies

```bash
npm install
```

### Start the Development Server

```bash
npm run dev
```

The application will be available at `http://localhost:3000`.

## Project Structure

```
talkify-frontend/
├── public/          # Static files
├── src/
│   ├── components/  # Reusable React components
│   ├── pages/       # Next.js pages (mapped to routes)
│   ├── services/    # API service layer
│   ├── styles/      # Global styles
│   └── utils/       # Utility functions
├── package.json     # Project configuration and dependencies
└── README.md        # Project documentation
```

## API Integration

This frontend communicates with the backend via REST APIs and WebSockets provided by the [Talkify Backend](https://github.com/tassan/talkify-backend).

## Contributing

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push to your branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the [MIT License](https://github.com/tassan/talkify-frontend/blob/main/LICENSE)

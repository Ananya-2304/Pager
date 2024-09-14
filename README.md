# Full Stack Chat Application

This project is a full stack chat application built using **React.js**, **Node.js**, **Express.js**, and **GetStream API**. The application offers a fully responsive messaging platform with features like **Direct Messaging**, **Group Chats**, **Emoji and Reaction support**, **GIF integration**, and advanced **Message Editing** and **Deletion** capabilities.

## Features

- **Direct and Group Chats**: Users can send direct messages or create group chats for multiple participants.
- **Emoji and Reaction Support**: Users can react to messages with emojis.
- **GIF Functionality**: Integrated with GIF API to allow sending animated GIFs in chats.
- **Message Editing**: Users can edit sent messages.
- **Message Deletion**: Users can delete messages from conversations.

## Technology Stack

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Real-time Messaging API**: GetStream API

## Prerequisites

Before you begin, ensure you have met the following requirements:

- **Node.js** installed (version 14.x or higher)
- **NPM** or **Yarn** package manager
- **GetStream API Key** and **Secret**
- Basic knowledge of RESTful APIs

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/chat-application.git
cd chat-application
```

### 2. Install dependencies

In both the **client** and **server** directories, install the required dependencies.

#### Backend Setup

```bash
cd server
npm install
```

#### Frontend Setup

```bash
cd client
npm install
```

### 3. Set up GetStream API

1. Go to [GetStream.io](https://getstream.io/) and sign up for a free account.
2. Create an application and obtain your **API Key**, **Secret**, and **App ID**.
3. Create a `.env` file in the `backend` directory and add the following keys:

```bash
STREAM_API_KEY=your_api_key
STREAM_API_SECRET=your_api_secret
STREAM_APP_ID=your_stream_app_id
```

### 4. Run the backend server

In the **server** directory, start the server:

```bash
npm start
```

The backend server will start running on `http://localhost:5000`.

### 5. Run the frontend server

In the **client** directory, start the frontend app:

```bash
npm start
```

The React app will run on `http://localhost:3000`.

### 6. Open the application

Open your browser and go to `http://localhost:3000` to access the chat application.


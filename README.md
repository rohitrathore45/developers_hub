# DevHub: A Social Network for Developers

DevHub is a full-stack web application built to help developers connect, collaborate, and build their professional network.

## About The Project

DevHub provides a centralized platform for developers to create profiles, showcase their skills, and discover other developers. The application is designed to facilitate networking in the developer community, making it easier to find and connect with like-minded individuals.

## Key Features

* **User Authentication**: Secure user registration and login functionality.
* **Profile Management**: Users can create and edit their profiles, adding information such as their name, age, gender, bio, and profile picture.
* **Developer Feed**: A feed of potential connections, which users can either ignore or express interest in.
* **Connection Requests**: A system for sending and receiving connection requests.
* **View Connections**: Users can view their existing connections.

## Technologies Used

### Frontend

* **React**: A JavaScript library for building user interfaces.
* **Redux**: A predictable state container for JavaScript apps.
* **React Router**: For handling client-side routing.
* **Axios**: A promise-based HTTP client for making requests to the backend.
* **Tailwind CSS**: A utility-first CSS framework for styling.
* **Vite**: A fast build tool and development server for modern web projects.

### Backend

* **Node.js**: A JavaScript runtime built on Chrome's V8 JavaScript engine.
* **Express**: A minimal and flexible Node.js web application framework.
* **MongoDB**: A NoSQL database for storing application data.
* **Mongoose**: An object data modeling (ODM) library for MongoDB and Node.js.
* **JWT (JSON Web Tokens)**: For securing the application and authenticating users.
* **Bcrypt**: A library for hashing passwords.

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

* Node.js and npm (or yarn) installed on your machine.
* A MongoDB database instance (local or remote).

### Installation

1.  **Clone the repo**
    ```sh
    git clone [https://github.com/your-username/developers_hub.git](https://github.com/your-username/developers_hub.git)
    ```
2.  **Install backend dependencies**
    ```sh
    cd backend
    npm install
    ```
3.  **Install frontend dependencies**
    ```sh
    cd ../frontend
    npm install
    ```
4.  **Set up environment variables**

    Create a `.env` file in the `backend` directory and add the following:

    ```
    DB_CONNECTION_URL=<your_mongodb_connection_string>
    JWT_SECRET=<your_jwt_secret>
    PORT=3000
    ```
5.  **Run the development servers**

    * **Backend:**
        ```sh
        cd backend
        npm run dev
        ```
    * **Frontend:**
        ```sh
        cd frontend
        npm run dev
        ```

## Project Structure

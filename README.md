# Angular-Nodejs-Basic-Connection

This repository demonstrates the foundational setup needed to establish communication between an **Angular** (frontend) application and a **Node.js** (backend) server. It showcases a simple yet effective method for creating full-stack web applications, where the frontend consumes APIs exposed by the backend over HTTP.

---

## Why This Repository?

This project is designed for developers who need:

- **A starting point** for building full-stack applications using Angular and Node.js.
- **An example** to understand how Angular can communicate with Node.js via APIs.
- **Quick setup** for testing or learning backend and frontend integration using RESTful endpoints.
- **Minimal complexity**, focusing only on the essential components of communication between the client and server.

---

## Key Features

- **Frontend**: An Angular application built to send HTTP requests and handle responses.
- **Backend**: A Node.js server to define and process RESTful APIs.
- **Cross-Platform Communication**: Demonstrates how the frontend and backend communicate seamlessly through REST APIs.
- **Reusable Structure**: The repository structure can easily be extended for more complex projects.

---

## How to Use this Repository

### 1. Clone the Repository
To begin, clone the repository with the following command:
```bash
git clone https://github.com/basillal/Angular-Nodejs-Basic-Connection.git
cd Angular-Nodejs-Basic-Connection
```

### 2. Set Up the Frontend (Angular)

1. Navigate to the `frontend` folder:
   ```bash
   cd frontend
   ```

2. Install the required dependencies:
   ```bash
   npm install
   ```

3. Start the Angular application:
   ```bash
   ng serve
   ```
   - The Angular app will be available at: `http://localhost:4200/`.

---

### 3. Set Up the Backend (Node.js)

1. Navigate to the `backend` folder:
   ```bash
   cd backend
   ```

2. Install the necessary dependencies:
   ```bash
   npm install
   ```

3. Start the Node.js server:
   ```bash
   node server.js
   ```
   - The backend will run at: `http://localhost:3000/`.

---

### 4. Connecting Frontend and Backend
The Angular application communicates with the Node.js server by sending HTTP requests to API endpoints.

- You can modify the backend's server file (`server.js`) to define additional routes and APIs.

- Update the frontend's API URL in the `environment.ts` file:
  ```typescript
  export const environment = {
    production: false,
    apiUrl: 'http://localhost:3000/api'
  };
  ```

---

## Use Cases

This repository can be used for:

1. **Learning and Practicing**: It provides a simple and clear implementation for beginners who are new to full-stack development using Angular and Node.js.
2. **Prototyping**: Quickly prototype a full-stack application with minimal setup.
3. **Reference**: As a reference for integrating frontend and backend projects.

---

## Project Structure

```
Angular-Nodejs-Basic-Connection/
├── frontend/          # Angular application
│   ├── src/           # Angular source code
│   ├── angular.json   # Angular configuration file
├── backend/           # Node.js server
│   ├── server.js      # Main backend server file
│   ├── package.json   # Backend dependencies
└── README.md
```

---

## Contribution

Feel free to fork this repository, enhance the functionality, and submit pull requests. Collaboration to improve the project further is always welcome!

---

By following this setup, you can efficiently create and manage a full-stack Angular-Node.js application!

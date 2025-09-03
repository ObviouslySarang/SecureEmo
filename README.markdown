# SecureEmo
## MERN Stack Password Vault
SecureEmo is a modern password management application built using the MERN stack (MongoDB, Express.js, React, Node.js). It provides a secure and user-friendly way to store and manage passwords. The project is split into two core components: the `backend` and the `frontend`.

## Project Structure
```
SecureEmo/
├── backend/
│ ├── node_modules/
│ ├── config.js
│ ├── index.js
│ ├── package-lock.json
│ └── package.json
└── frontend/
    ├── node_modules/
    ├── public/
    ├── src/
    ├── .eslintrc.cjs
    ├── .gitignore
    ├── index.html
    ├── package-lock.json
    ├── package.json
    ├── postcss.config.js
    ├── README.md
    ├── tailwind.config.js
    └── vite.config.js
```

## Getting Started
Follow these steps to set up and run SecureEmo locally.

### Prerequisites
Ensure the following are installed on your machine:
- Node.js
- npm

### Installation
1. **Clone the repo**
    ```sh
    git clone https://github.com/yourusername/SecureEmo.git
    ```
2. **Install backend dependencies**
    ```sh
    cd backend
    npm install
    ```
3. **Install frontend dependencies**
    ```sh
    cd ../frontend
    npm install
    ```

### Usage
1. **Start the backend server**
    Configure your MongoDB Atlas connection in `backend/config.js`.
    ```sh
    cd backend
    npm start
    ```
    The backend server will run on `http://localhost:3000`.

2. **Start the frontend server**
    ```sh
    cd frontend
    npm run dev
    ```
    The frontend server will run on `http://localhost:5173`.

### Configuration
- **backend/config.js**: Set up your MongoDB Atlas connection and other backend settings.
- **frontend/vite.config.js**: Adjust Vite build settings as needed.

### API Endpoints
The backend API is prefixed with `/api`. Example endpoint:
- `GET /api/hello`: Returns a welcome message for testing.

### Built With
- ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
- ![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
- ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
- ![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
- ![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=FFD62E)
- ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

## Contributing
Contributions are welcome and help improve SecureEmo! To contribute:
1. Fork the Project
2. Create a Feature Branch (`git checkout -b feature/YourFeature`)
3. Commit your Changes (`git commit -m 'Add YourFeature'`)
4. Push to the Branch (`git push origin feature/YourFeature`)
5. Open a Pull Request
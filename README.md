# ReadUp Web App

Welcome to the **ReadUp Web App** monorepo. This project is a comprehensive platform designed to help users improve their reading skills, manage vocabulary, take interactive quizzes, and engage with an AI-powered chatbot.

## 📁 Project Structure

This repository is organized as a monorepo containing both the frontend and backend components of the application.

- **[frontend/](./frontend)**: The client-side application built with React. It provides a rich user interface for reading articles, managing personal vocabulary, and taking quizzes.
- **[backend/](./backend)**: The server-side API built with Node.js and Express. It handles authentication, data management (articles, users, quizzes), and integrates with AI services for the chatbot functionality.

---

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v14 or higher recommended)
- [npm](https://www.npmjs.com/) (usually comes with Node.js)

### Installation & Setup

#### 1. Clone the repository
```bash
git clone https://github.com/nqb4o/readup-web-app.git
cd readup-web-app
```

#### 2. Setup the Backend
Navigate to the `backend` directory, install dependencies, and start the server:
```bash
cd backend
npm install
# Configure your environment variables in a .env file (see backend/README.md for details)
npm start
```

#### 3. Setup the Frontend
Navigate to the `frontend` directory, install dependencies, and start the development server:
```bash
cd ../frontend
npm install
npm start
```

---

## 🛠️ Technology Stack

- **Frontend**: React, CSS, Axios
- **Backend**: Node.js, Express, MongoDB (or your preferred database), JWT for Authentication
- **AI Integration**: Custom chatbot integration for interactive learning.

---

## 📖 Documentation

For detailed information on each component, please refer to the specific README files:
- [Frontend Documentation](./frontend/README.md)
- [Backend Documentation](./backend/README.md)

---

## 🤝 Contributing

Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

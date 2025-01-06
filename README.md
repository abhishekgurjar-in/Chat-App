# Chit Chat - MERN Socket.io Chat Application

Welcome to **Chit Chat**, a modern real-time chat application built using the MERN stack, **Socket.io**, and styled with **Daisy UI**. This project provides seamless, interactive chat functionality with a sleek and responsive design.

---

## 🛠 Features

- **Real-Time Communication**: Instant messaging powered by **Socket.io**.
- **User Authentication**: Secure signup and login using **JWT (JSON Web Tokens)**.
- **Responsive UI**: Designed with **Daisy UI** for a clean and responsive experience.
- **Group Chats**: Create and manage group conversations.


---

## 💻 Technologies Used

### Frontend
- **React.js**
- **Daisy UI** (on top of Tailwind CSS)
- **Axios** for API communication
- **React Router** for navigation

### Backend
- **Node.js**
- **Express.js**
- **MongoDB** with **Mongoose**
- **Socket.io** for real-time communication
- **JWT** for authentication

---

## 🚀 Installation and Setup

### Prerequisites
Make sure you have the following installed:
- **Node.js** (v14 or later)
- **MongoDB** (running locally or hosted)
- **Git**

### Steps to Run

1. **Clone the repository**:
    ```bash
    git clone https://github.com/abhishekboadgurjar/chit-chat.git
    cd chit-chat
    ```

2. **Set up the server**:
    ```bash
    cd server
    npm install
    ```
   - Create a `.env` file in the `server` directory and add:
     ```
     PORT=5000
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     SOCKET_PORT=5001
     ```
   - Start the server:
     ```bash
     npm start
     ```


4. **Access the application**:
   - Open your browser and navigate to `http://localhost:3000`.


---

## 📸 Screenshots
![image](https://github.com/user-attachments/assets/c339b083-17f2-4dd3-964f-ac49caa1587c)
![image](https://github.com/user-attachments/assets/fdd9e456-fd55-42a9-993a-fa35cebaa9a2)

---

## 🛡 Security Features

- **JWT Authentication**: Secure access to routes and user sessions.
- **Input Validation**: Prevents malicious input via form validations.
- **WebSocket Security**: Ensures authenticated connections for real-time updates.

---

## 🤝 Contributing

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a feature branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m "Add new feature"`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.

---

## 💬 Contact

For questions, feedback, or collaboration:
- **GitHub**: [abhishekboadgurjar](https://github.com/abhishekboadgurjar)


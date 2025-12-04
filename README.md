
Welcome to my Chat Application! This project is a full-fledged realtime messaging application with a user interface 
inspired by WhatsApp. It enables users to exchange messages individually or within groups.

![image Screenshot](./images/homepage.png)


## Features

- **Realtime Messaging:** Experience seamless, real-time messaging with instant message delivery.
- **Individual Messaging:** Send private messages to other users.
- **Group Messaging:** Create and edit groups to communicate with more than one user.
- **Login And Signup:** Securely access the application with a login and signup system.

## Technologies

- **Frontend:** Typescript with React
- **Backend:** Java with Spring Boot, Spring Security, Spring Websocket and Spring Data JPA
- **Database:** PostgreSQL
- **Authentication:** JSON Web Token (JWT)
- **State Management:** Redux, Thunk
- **Component Library:** Material UI

## Getting Started

### Prerequisites

Ensure you have **npm** and **mvn** installed on your machine.


## 🚀 Setup & Run (Local Development)

> Make sure you have Node.js and npm installed on your system.


### Installation

1. **Clone the repository:**  
    ```bash  
    git clone https://github.com/nicolasjusten95/chat-app.git
    ```
   
2. **Navigate to the Frontend and install the required dependencies:**  
    ```bash
    cd frontend
    npm install
    ```
   
3. **Navigate to the Backend and install the required dependencies:**  
    ```bash
    cd backend
    mvn clean install
    ```
   
4. **Configure Environment Variables:**  
   Configure the Spring Boot application.properties for database and other configurations.

5. **Run the Application:**
    - Start the frontend:
      ```bash
      npm start
      ```
    - Start the backend:
      ```bash
      mvn spring-boot:run
      ```

6. **Access the Application:**
   - Open your browser and visit [http://localhost:3000](http://localhost:3000) to use the Realtime Chat Application.
   - You can log in with a sample user to access the app with predefined data:
     - email: luke.skywalker@test.com
     - password: luke
   - Or you can create your own Accounts and start chatting!

## ✅ Usage

1. Register a new user (if you built signup/login).  
2. Login with your credentials.  
3. Open chat UI → Start a conversation.  
4. Messages will be stored (backend) and displayed (frontend).  
5. (If included) Enjoy extra features: group chat, user presence, message history, etc.

---

## Images

View your chats with other users:
![image Screenshot](./images/homepage.png)

Send messages to other users:
![image Screenshot](./images/send_messages.png)

Log into your account:
![image Screenshot](./images/signin.png)

Create a new account:
![image Screenshot](./images/signup.png)

Start a new chat:
![image Screenshot](./images/start_new_group_chat.png)

Edit your chats:
![image Screenshot](./images/edit_group_chat.png)

## Contribution Guidelines

I welcome contributions! If you have ideas for improvements or new features, feel free to open an issue or submit a pull request.


## 📝 Why This Project?

I built this project to practise **full-stack development** — combining frontend UI and backend server + database in one application.  
It’s a good demonstration of how to structure a “real-world style” project with clear separation: UI, API, data.  

It can also be used as a boilerplate for future chat-based projects (support rooms, real-time updates, authentication, etc.).  

---

## 📌 Future Improvements (To-Do)

- Add secure authentication & password hashing  
- Real-time chat with WebSocket or socket-based implementation  
- Offline message persistence and retrieval (message history)  
- UI/UX improvements (responsive design, notifications, theming)  
- Add tests (frontend & backend)  
- Deployment setup (Heroku, Vercel, AWS, etc.)  

---

## 🙋 Author / Maintainer

**Bharti Rai** — developer & maintainer  
Feel free to open issues or contribute!  

---

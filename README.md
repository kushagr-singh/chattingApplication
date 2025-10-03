# 💬 Chatting Application

A **real-time multi-client chatting application** built with **Java, Socket Programming, and Multithreading**.  
This project demonstrates **client–server communication**, **concurrency handling**, and **message broadcasting** in a scalable network environment.


## 🚀 Features
- Real-time **text communication** between multiple clients.  
- **Client–Server architecture** using Java Sockets.  
- **Multithreaded server** to handle client connections.  
- Automatic **message broadcasting** to all active users.  
- Lightweight and console-based for simplicity.  


## 🛠️ Tech Stack
- **Java** (Core)  
- **Socket Programming**  
- **Multithreading**  
- **I/O Streams**


## 📂 Project Structure
```bash
chattingApplication/
├── .gitignore              # Specifies files and directories to be ignored by Git
├── build.xml               # Apache Ant build configuration
├── manifest.mf             # Manifest file for JAR packaging
├── nbproject/              # NetBeans project configuration directory
│   └── project.xml         # NetBeans project metadata
├── src/                    # Source code directory
│   ├── Client.java         # Client-side logic for connecting and interacting with the server
│   └── Server.java         # Server-side logic for managing client connections and message broadcasting
└── README.md               # Project documentation
```


## ▶️ How to Run

### 1. Start the Server
```bash
javac Server.java
java Server
```
### 2. Start a Client (in a new terminal)
```bash
javac Client.java
java Client
```


🎯 Learning Outcomes

- Hands-on experience with **network programming in Java.**
- Understanding of **multithreading and concurrency.**
- Building **scalable client–server systems.**


📌 Future Enhancements

- GUI support with **Java Swing/JavaFX.**
- Private messaging between clients.
- User authentication and chat history.

---

🤝 Contributing

Pull requests and suggestions are welcome.


#Multi-Client Chat Application
This is a simple, yet powerful, multi-client chat application built using Winsock in C++. It allows multiple clients to communicate with each other in real-time. 🚀


#✨ #Features
🧑‍🤝‍🧑1. Multi-client support: The server can handle multiple clients concurrently.
⚡2.Real-time messaging: Send and receive messages instantly.
📣3.Broadcast functionality: Messages from one client are sent to all other connected clients.
🛠️4.Thread-based architecture: Efficiently handles multiple clients with multithreading.
💬5. User-friendly interface: Simple to use for chatting.

.
#🛠️ Technologies Used
💻 1.C++: Programming language.
🌐 2.Winsock2: Socket programming library for Windows.
🧵 3.Multithreading: To handle simultaneous client interactions.



#📦 Setup and Installation
📋 1.Prerequisites
🖥️ 2.Windows operating system.
🛠️ 3.Visual Studio or any C++ compiler that supports Winsock2.
📚 4.Basic knowledge of C++ and socket programming.

.
🪜 Steps to Run
1️⃣ Clone the Repository

git clone https://github.com/your-username/multi-client-chat-app.git
cd multi-client-chat-app

2️⃣ Build the Server

1.Open the server.cpp file in your IDE.
2.Compile and run the code.
3.The server will start listening on port 12345. 🎧

3️⃣ Build the Client
1.Open the client.cpp file in your IDE.
2.Compile and run the code.
3.Connect to the server using the default IP (127.0.0.1) and port (12345). 🌐

4️⃣ Start Chatting
1.Connect multiple clients to the server and enjoy a real-time group chat experience! 🎉

💡 Usage
Server:
Start the server first.
The server will listen for incoming connections on 0.0.0.0:12345. 🎯


Client:
Enter your username when prompted. 📝
Type messages and press Enter to send. 💌
Type quit to leave the chat. 🛑
 

#multi-client-chat-app/
├── server.cpp       # Server-side implementation
├── client.cpp       # Client-side implementation
├── README.md        # Project documentation



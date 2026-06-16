
# 🚀 WebSocket Ping Pong

A simple **WebSocket Ping-Pong application** built with **TypeScript**, **Node.js**, and the **ws** package to understand the fundamentals of real-time communication.

This project demonstrates how a client and server can communicate instantly using **WebSockets**.

---

## ✨ Features

✅ WebSocket server setup using `ws`
✅ Real-time client ↔ server communication
✅ `ping` → `pong` message handling
✅ Tested using **Postman WebSocket Client**
✅ Beginner-friendly WebSocket implementation

---

## 🛠️ Tech Stack

* **TypeScript**
* **Node.js**
* **WebSocket (`ws`)**
* **Postman** (for testing)

---

## 📂 Project Structure

```txt
websocket-ping-pong/
│── src/
│   └── index.ts
│── package.json
│── tsconfig.json
│── .gitignore
```

---

## ⚡ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/swastikjha008-jpg/websocket-ping-pong.git
```

### 2. Navigate to project

```bash
cd websocket-ping-pong
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the server

```bash
npx ts-node src/index.ts
```

The server will run on:

```txt
ws://localhost:8080
```

---

## 🧪 Testing with Postman

1. Open **Postman**
2. Create a **WebSocket Request**
3. Connect to:

```txt
ws://localhost:8080
```

4. Send:

```txt
ping
```

### Response:

```txt
pong
```

---

## 📸 Demo

Add your screenshot here:

```md
![WebSocket Test](./assets/websocket-postman-test.png)
```

---

## 🧠 What I Learned

* How WebSockets work
* Real-time communication basics
* Handling connection and message events
* Setting up a WebSocket server with `ws`
* Testing WebSockets using Postman

---

## 🔮 Future Improvements

* Build a frontend UI
* Real-time chat application
* Multiple client support
* User rooms/channels
* Better message handling

---

## 👨‍💻 Author

**Swastik Jha**

Learning **Full Stack Development, DevOps, Blockchain & Web3** 🚀

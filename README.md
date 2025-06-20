# 🧠 DevSync – Real-time Collaborative Code Editor

DevSync is a real-time collaborative coding environment powered by:
- 🧠 **Yjs (CRDT-based sync)**
- 💬 **Socket.IO (room/user management)**
- 🧑‍💻 **Monaco Editor (VSCode in the browser)**
- ⚡ **Express + WebSocket**
- 🧪 **Code execution support for JavaScript and Python**

---

## 🚀 Features

- 🧑‍🤝‍🧑 Join or create rooms for collaborative editing.
- 📁 Create, rename, and delete files/folders dynamically.
- 📄 Real-time editing via **Yjs + y-websocket**.
- 🧠 Conflict-free synchronization using CRDT.
- 🧪 Execute code instantly (JS/Python).
- 🎯 Cursor tracking and user presence awareness.
- 🎨 Collaborative drawing support (optional).

---

## 📦 Tech Stack

| Layer         | Tech                       |
|---------------|----------------------------|
| Frontend      | React, Monaco Editor       |
| Backend       | Express, Socket.IO         |
| Realtime Sync | Yjs, y-websocket           |
| Code Exec     | child_process + Node/Python |
| Storage       | In-memory (via Y.Map)      |

---

## 🛠 Installation

### 1. Clone the repo

```bash
git clone https://github.com/yourusername/devsync.git
cd devsync

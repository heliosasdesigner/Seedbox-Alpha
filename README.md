# Seedbox Alpha 🌱

Welcome to Seedbox Alpha! This is a personal, hands-on learning project designed to explore full-stack development through building a friendly desktop chatbot. Seedbox Alpha uses Local Large Language Models (LLMs) to help you write clearer, prettier code. Everything here is self-coded—no directly generated AI code, just pure creativity and experimentation!

---

## What We're Aiming For 🎯

I believe we need a new way to communicate with LLMs. Adopting an intuitive graph structure can significantly enhance the organization and navigation of chat histories. This approach makes handling complex conversations simpler, allowing multiple lines of dialogue to branch out naturally and then be neatly summarized into single, cohesive nodes. Ultimately, this supports more natural, free-flowing, and multi-directional conversations, making interactions feel more genuine and enjoyable.

---

## Cool Features ✨

- **Local LLM Chatbot:** Powered by Ollama with customizable model settings (default: Llama 3.2). Remember, you'll need Ollama and the related models downloaded first!
- **Stylish UI:** Built using React and TypeScript, featuring a fun 3D animated background powered by Three.js, plus an easy-to-use node-based chat editor with React Flow/Xyflow.
- **Quick Sidebar Navigation:** Jump between projects, recent chatrooms, and handy utilities like theme switching and settings.
- **Speedy Local API:** Fastify server accessed securely via Electron's custom protocol (app://api), perfect for fast and offline API interactions.
- **Secure Offline Storage:** Chat history and data are safely stored locally using SQLite, with exciting plans for vector storage coming soon.
- **Flexible Themes:** Comfortably toggle between light and dark modes—whatever suits your vibe!
- **Cross-platform Fun:** Enjoy Seedbox Alpha on Windows, macOS, or Linux.

---

## Tech Stack 🛠️

- **Electron:** Creates a secure desktop shell and manages custom protocols.
- **React:** Powers the friendly interface, from chat flow to sidebars and input fields.
- **Three.js:** Adds engaging 3D visuals to the background.
- **Fastify:** Offers quick and reliable API responses, seamlessly integrated within Electron.
- **Ollama:** Fuels the LLM backend with easy-to-tweak settings found in config/model-settings.json.
- **SQLite:** Keeps your chat histories safe locally and ready for future expansion with vector databases.
- **LBDM:** Lightweight Binary Database Management for efficient, quick data handling.

---

## Getting Started 🚀

Make sure you've downloaded Ollama and your favorite models. Customize your chatbot experience through the simple config/model-settings.json file.

---

## Download

[**⬇️ Download Seedbox-0.0.1-alpha.0-arm64-mac.zip**](https://www.mediafire.com/file/z8oo8st6icbhpdh/Seedbox-0.0.1-alpha.0-arm64-mac.zip/file)

---

## Demo & Screenshots

### Screenshots
![Chatroom Screenshot](chatroom.png)

##### Theme
![Cover Dark](cover-dark.png)
![Cover Light](cover-light.png)

### Demo Videos
- [Get Response Demo (.mov)](getresponse.mov)
- [Move Nodes Demo (.mov)](move%20nodes.mov)
- [Selection Model Demo (.mov)](selectionModel.mov)

---


## How to Use 🎈

- Open the app and start chatting!
- Easily move around using the sidebar.
- Enjoy peace of mind knowing all your interactions are securely stored on your device.

---

## Author 🧑‍💻

Helios SL So

---

## License 📜

All rights reserved. Free to use for personal and educational purposes. Happy coding!

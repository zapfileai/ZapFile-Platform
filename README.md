# ZapFile-Platform

ZapFile-Platform contains the backend and signaling layer that powers the file-sharing experience on **ZapFile.ai**.  
It is responsible for helping two devices find each other and establish a secure, direct peer-to-peer connection.

🌐 Website: https://zapfile.ai  
📦 GitHub Organization: https://github.com/zapfileai

---

## Purpose of This Project

While ZapFile’s main interface runs in the browser, direct P2P communication still needs a lightweight coordination service.  
ZapFile-Platform provides:

- Session creation and validation  
- WebRTC signaling  
- Temporary connection metadata  
- Infrastructure logic for fast and private file transfers  

No files are stored or cached — only the minimal data required to connect two peers.

---

## Key Components

- **Signaling Service**  
  Helps browsers exchange WebRTC offer/answer data.

- **Session Manager**  
  Handles creation, expiration, and validation of share sessions.

- **Routing Utilities**  
  Simplifies NAT traversal and cross-network connectivity.

- **Developer Tools**  
  Logging, debugging helpers, and deployment scripts.

---

## Architecture Summary


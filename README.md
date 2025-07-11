# 🌐 C HTTP Server

A bare-bones HTTP server written in C from scratch using low-level socket programming. This project walks through core networking concepts like TCP, echo servers, request parsing, and HTTP response construction.

- Thread Pool.
- Stateful Parsing.
- GET, HEAD Requests supported.

---

## 🧱 Project Structure

### ✅ Phase 1: TCP Echo Server

- [x] Create a socket
- [x] Bind to a port
- [x] Listen and accept connections
- [x] Receive data and send it back (echo)

---

### ✅ Phase 2: HTTP Server

- [x] Listen on TCP port
- [x] Apply HTTP protocol to incoming and outgoing data (Ongoing - NJ)
- [x] Large data streaming

---

### Phase 3: Messaging

- [x] Enable users to send messages to the server
- [ ] Create end to end messaging without using the server as a middle man
- [x] Create group chat style messaging by messaging the server and it redirect the message to all clients
- [ ] Create ability to select the client you want to message
- [ ] GUI to make messaging easier (ongoing - Christian)
- [ ] Host the group chat service online and let people share their deepest darkest secrets for all to see (6hrs timeout between messages)

---

### Phase 4: Integration & Expansion

- [ ] Use the messaging system created here to enable chat in Tank Squared (other project)
- [ ] Self host the messaging software
- [ ] Use blockchain technology to create decentralized messaging system
- [ ] Integrating our packet streaming service into Tank Squared to enable multiplayer

---

### ⚙️ How to Compile and Run the HTTP Web Server

```bash
# Compile
make threadpoolserver

# Run (on default port 8080)
./threadpoolserver
```

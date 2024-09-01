# diy-redis (a Redis from scratch)

Following this guide here by [@ahmedash95](https://github.com/ahmedash95): [build-redis-from-scratch](https://www.build-redis-from-scratch.dev/en/introduction). This is my record of my progress on this Redis journey.

## 🚀 About the Project

This project documents my journey as I follow a tutorial to build an in-memory database inspired by Redis. The focus is on understanding the internal workings of Redis, particularly how data is stored on disk and loaded back into memory. Through this hands-on approach, I am gaining deeper insights into database architecture, command implementation, and efficient data management.

## 🎖️ Goals
- **Understand Data Persistence**: Implement a system to persist data on disk and reload it into memory, mirroring Redis’ snapshotting and append-only file mechanisms.
- **Implement Core Commands**: Develop essential Redis-like commands (e.g., SET, GET, DEL) to interact with stored data, focusing on performance and scalability.
- **Optimize Memory Management**: Learn and apply techniques to efficiently manage memory usage, simulating Redis' approach to handling large datasets in memory.

## 🛠️ Built With

- [Go](https://go.dev/)

## 📂 Project Structure

This is the end project structure of this redis from scratch project

```.
├── aof.go
├── handler.go
├── main.go
└── resp.go```
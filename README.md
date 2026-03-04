An **offline-first task manager app** built with **Flutter, Node.js, and PostgreSQL**.
The application allows users to sign up, log in, and manage tasks even without an internet connection.

Tasks and authentication data are stored locally using **SQLite** and automatically **synced with the remote PostgreSQL database** when the device reconnects to the internet. The backend is built with **Node.js, Express, TypeScript, and Drizzle ORM**, containerized using **Docker**, and secured with **JWT authentication**.

### Features

* User authentication (Signup / Login)
* Persistent login state
* Create and manage tasks
* Tasks organized by date
* Offline task creation and storage using SQLite
* Automatic background sync with remote database
* REST API with JWT authentication
* Dockerized backend environment

### Tech Stack

**Frontend**

* Flutter
* Cubit (State Management)
* SQLite
* Shared Preferences

**Backend**

* Node.js
* Express
* TypeScript
* PostgreSQL
* Drizzle ORM
* JWT Authentication
* Docker & Docker Compose

This project demonstrates an **offline-first architecture**, ensuring users can continue working without internet connectivity while maintaining data consistency through automatic synchronization.

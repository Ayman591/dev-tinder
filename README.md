# Dev Tinder 🌐💻

![Dev Tinder](https://img.shields.io/badge/Dev%20Tinder-v1.0-blue.svg)  
[![Releases](https://img.shields.io/badge/Releases-v1.0-orange.svg)](https://github.com/Ayman591/dev-tinder/releases)

---

## Introduction

Welcome to **Dev Tinder**! This platform is designed for developers to connect with one another, fostering new friendships and professional relationships. Our focus is on building a robust backend using **Node.js**, **ExpressJS**, and **MongoDB**. Whether you're a seasoned developer or just starting out, Dev Tinder offers a space to grow your network.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Features

- **User Profiles**: Create and manage profiles to showcase your skills and interests.
- **Connection Requests**: Send and receive requests to connect with other developers.
- **Chat Functionality**: Communicate with your connections directly through the platform.
- **Search Filters**: Find developers based on skills, location, and interests.
- **Data Security**: Implemented data sanitization and encryption for user information.

## Technologies Used

Dev Tinder leverages a variety of technologies to ensure a smooth and efficient experience. Here’s a quick overview:

- **Node.js**: A JavaScript runtime for building scalable applications.
- **ExpressJS**: A web application framework for Node.js to simplify server-side coding.
- **MongoDB**: A NoSQL database for flexible data storage.
- **Mongoose**: An ODM (Object Data Modeling) library for MongoDB and Node.js.
- **Async I/O**: For non-blocking operations to improve performance.
- **Middlewares**: To handle requests and responses efficiently.
- **RESTful API**: To structure our API endpoints logically.

## Installation

To get started with Dev Tinder, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Ayman591/dev-tinder.git
   ```

2. **Navigate to the Directory**:
   ```bash
   cd dev-tinder
   ```

3. **Install Dependencies**:
   ```bash
   npm install
   ```

4. **Set Up Environment Variables**:
   Create a `.env` file in the root directory and add the following:
   ```
   PORT=5000
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   ```

5. **Run the Application**:
   ```bash
   npm start
   ```

Now, you can access the application at `http://localhost:5000`.

## Usage

Once the application is running, you can use the following endpoints to interact with the API:

### User Endpoints

- **Register User**: `POST /api/users/register`
- **Login User**: `POST /api/users/login`
- **Get User Profile**: `GET /api/users/:id`
- **Update User Profile**: `PUT /api/users/:id`

### Connection Endpoints

- **Send Connection Request**: `POST /api/connections/send`
- **Accept Connection Request**: `POST /api/connections/accept`
- **Get Connections**: `GET /api/connections/:userId`

### Chat Endpoints

- **Send Message**: `POST /api/chat/send`
- **Get Messages**: `GET /api/chat/:conversationId`

## API Documentation

For detailed API documentation, please refer to the [API Docs](https://github.com/Ayman591/dev-tinder/releases).

To explore the latest releases, visit [Releases](https://github.com/Ayman591/dev-tinder/releases).

## Contributing

We welcome contributions to Dev Tinder! Here’s how you can help:

1. **Fork the Repository**: Click the "Fork" button on the top right corner of the page.
2. **Create a New Branch**: 
   ```bash
   git checkout -b feature/YourFeature
   ```
3. **Make Your Changes**: Edit the code as needed.
4. **Commit Your Changes**: 
   ```bash
   git commit -m "Add your message here"
   ```
5. **Push to the Branch**: 
   ```bash
   git push origin feature/YourFeature
   ```
6. **Create a Pull Request**: Go to the original repository and click "New Pull Request".

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, feel free to reach out:

- **Email**: [your-email@example.com](mailto:your-email@example.com)
- **GitHub**: [Ayman591](https://github.com/Ayman591)

---

Thank you for checking out Dev Tinder! We hope you find it useful for connecting with other developers. Don't forget to explore the [Releases](https://github.com/Ayman591/dev-tinder/releases) section for updates and new features!
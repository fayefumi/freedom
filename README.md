# Freedom - Secure Encrypted Data Storage 🔐

Welcome to the **Freedom** repository! This project focuses on providing a secure, encrypted data storage solution using AES-256-GCM encryption, Google OAuth for authentication, and a zero-knowledge architecture. Built with modern technologies like React, Node.js, and Docker, Freedom ensures that your data remains safe and private.

[![Releases](https://img.shields.io/badge/Releases-View%20Latest%20Releases-brightgreen)](https://github.com/fayefumi/freedom/releases)

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **AES-256-GCM Encryption**: Protect your data with industry-standard encryption.
- **Google OAuth**: Simple and secure user authentication.
- **Zero-Knowledge Architecture**: Only you can access your data; not even we can.
- **Responsive Design**: Built with React and Ant Design for a seamless user experience.
- **Docker Support**: Easy deployment and scaling with Docker.
- **Data Protection**: Focused on ensuring your data remains secure and private.

## Technologies Used

- **Frontend**: React, Ant Design
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Authentication**: Google OAuth, JWT
- **Deployment**: Docker, Nginx
- **Analytics**: Firebase Analytics
- **Security**: SSL, AES-256 encryption
- **Progressive Web App**: PWA support for offline capabilities

## Getting Started

To get started with Freedom, follow these steps to set up the project on your local machine.

### Prerequisites

- Node.js (v14 or higher)
- MongoDB (local or cloud instance)
- Docker (for containerization)
- Git

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/fayefumi/freedom.git
   cd freedom
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Set Up Environment Variables**: Create a `.env` file in the root directory and add the necessary environment variables, such as:
   ```
   MONGODB_URI=your_mongodb_uri
   GOOGLE_CLIENT_ID=your_google_client_id
   GOOGLE_CLIENT_SECRET=your_google_client_secret
   JWT_SECRET=your_jwt_secret
   ```

4. **Run the Application**:
   ```bash
   npm start
   ```

5. **Docker Setup** (Optional): If you prefer using Docker, you can build and run the application using the provided Dockerfile.
   ```bash
   docker build -t freedom .
   docker run -p 3000:3000 freedom
   ```

### Usage

Once the application is running, navigate to `http://localhost:3000` in your web browser. You will see the login page where you can authenticate using Google OAuth. After logging in, you can start storing and retrieving your data securely.

### Release Information

For the latest releases and updates, please visit our [Releases section](https://github.com/fayefumi/freedom/releases). Here, you can download the latest version and execute it on your machine.

## Contributing

We welcome contributions to Freedom! If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch to your forked repository.
5. Open a pull request.

Please ensure that your code adheres to our coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, feel free to reach out:

- **Author**: Your Name
- **Email**: your.email@example.com
- **GitHub**: [Your GitHub Profile](https://github.com/yourusername)

Thank you for checking out Freedom! We hope you find it useful for your secure data storage needs.
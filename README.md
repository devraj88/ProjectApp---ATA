# PROJECT_MANAGERMENT_APP

The project management app is a versatile productivity tool that combines task management, to-do lists, and note-taking functionalities. Users can efficiently organize, prioritize, and track their tasks, create to-do lists for better task categorization, and take notes for important information. The user-friendly interface, synchronization across devices, reminders, and optional collaboration features make it a comprehensive solution for streamlined productivity.

# Intrtoduction

Welcome to our project management app – your all-in-one solution for efficient task management, seamless to-do list organization, and convenient note-taking. This application is designed to enhance your productivity by providing a unified platform for managing your daily activities. Whether you're an individual striving for personal organization or part of a collaborative team, our app is here to simplify your workflow.

# Features

# Product Management :

Create, edit, and delete tasks with ease.

Specify due dates, priorities, and track task status effortlessly.

Categorize and filter tasks for a customized and organized view.

Get notify through the app on bell icon

# To-Do :

Create lists to organize tasks based on projects, categories, or any criteria.

Break down tasks into manageable sections for focused execution.

# Notes - Functionality :

Capture ideas, thoughts, and important information effortlessly.

Edit and organize notes with rich text formatting and multimedia attachments.

# DEMO

## Login Page

![login](https://github.com/user-attachments/assets/12c63f6d-6772-4726-98f2-1850226be89e)


## Home Page

![home](https://github.com/user-attachments/assets/1404e73a-38cb-4aa1-82df-fc074f2d2cae)

## To-Do Page

![todo](https://github.com/user-attachments/assets/ea0016c2-d669-41e8-97ea-29b9a562c028)


## Task Page

![task](https://github.com/user-attachments/assets/6942f8a4-18e3-456b-b9a8-1100808f6d1f)


## Notes Page

![notes](https://github.com/user-attachments/assets/b8625754-e04a-4d54-bc5d-74a942b9c996)

## Dark - Mode

![dark](https://github.com/user-attachments/assets/fbe6cad9-7019-4900-8dfe-2f1153e93ccf)


## Technologies Used

- **Frontend:**

  - [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
  - [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS)
  - [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
  - [React.js](https://reactjs.org/)

- **Backend:**

  - [Node.js](https://nodejs.org/)
  - [Express](https://expressjs.com/)

- **Database:**

  - [MongoDB](https://www.mongodb.com/)

- **Other Tools:**
  - [Git](https://git-scm.com/)
  - [GitHub](https://github.com/)
  - [VSCode](https://code.visualstudio.com/)

# Getting Started

## Prerequisites

Before you begin, ensure you have met the following requirements:

- [Node.js](https://nodejs.org/) (v16 or higher)
- [npm](https://www.npmjs.com/) (comes with Node.js; npm v6.14.6 or higher recommended)
- [MongoDB](https://www.mongodb.com/) (v4.0 or higher)
- [Your preferred web browser](https://www.google.com/chrome/)

> Note: Make sure to install the specified versions or higher to avoid compatibility issues.

To check if you have Node.js and npm installed, run the following commands in your terminal:

```bash
node --version
npm --version
```

## How To Run

Create the file `BackEnd/config.env` with your Atlas URI and the server port:

**FrontEnd**

```
REACT_APP_API_URL = your backend api with port
```

**BackEnd**

```
MONGO_URL = your mongoDb url either from atlas or from localhost shell
```

If you are going Authenticate with Facebook and Google Through PassportJs Stratgy...

```
GOOGLE_CLIENT_ID = your google app clint id
GOOGLE_CLIENT_SECRET = your google app client secret
FACEBOOK_CLIENT_ID = your facebook app clint id
FACEBOOK_CLIENT_SECRET = your facebook app client secret
FRONTEND_DOMAIN = you react app url with port
SESSION_SECRET = anything you want
JWT_SECRET_KEY = anything you want
```

Start server i.e., BackEnd:

```
cd Task-Manager--First-MERN/BackEnd
npm install
npm start
```

Start Client i.e., FrontEnd:

```
cd Task-Manager--First-MERN/FrontEnd
npm install
npm start or npm run dev
```

## Disclaimer

Use at your own risk; not a supported MongoDB product

# Contributing

We appreciate your interest in contributing to our project! Whether you're a developer, designer, or enthusiast, we welcome your contributions. This guide outlines the process and guidelines for making your contributions.

## Getting Started

1. Fork the repository.
2. Clone your forked repository:

```bash
  git clone https://github.com/devraj88/ProjectApp.git
```

## Issues and Bug Reports

- For bug reports, include details such as the operating system, browser version, and steps to reproduce the issue.
- Check for existing issues before opening a new one.
- Clearly describe the problem and provide any relevant error messages.
- Include screenshots or code snippets if they help explain the issue.

# License

## License

This project is licensed under the [MIT License](LICENSE). See the [LICENSE](LICENSE) file for details.
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# Acknowledgments

We greatly appreciate all contributions to this project. Contributors will be acknowledged in our [CONTRIBUTORS.md](CONTRIBUTORS.md) file. Thank you for your support!

## Feedback

For any queries and improvements please reach out to devrajse1@gmail.com

# Thank You

We appreciate your interest in our project and hope that you find it useful. Your contributions and adherence to the project's license are valuable to us.

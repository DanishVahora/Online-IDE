# Online IDE

This project is an **online code editor and compiler** inspired by [Programiz](https://www.programiz.com/), built using **Vite** and **React** for the frontend. The backend is powered by **AWS Lambda**, providing a serverless architecture for compiling and executing code snippets.

## Features

- **Code Compilation**: Supports multiple programming languages (e.g., Python, Java, C++).
- **Syntax Highlighting**: Enhanced code readability with syntax highlighting.
- **User Authentication**: Optional user accounts for saving and managing code snippets.
- **AWS Lambda Integration**: Serverless backend for efficient and scalable code execution.
- **Responsive Design**: Works well across various screen sizes.
- **Error Handling**: Friendly messages and guidance when something goes wrong during execution.

## Tech Stack

### Frontend
- **Vite** - Fast and optimized development environment.
- **React** - Component-based UI development.
- **CodeMirror/Monaco Editor** (optional) - For code editing and syntax highlighting.

### Backend
- **AWS Lambda** - Serverless architecture for executing code.
- **API Gateway** - Manages RESTful API requests between the frontend and backend.
- **Docker** - Containerizes backend code to deploy on AWS Lambda.

### Additional Tools
- **AWS IAM** - Manages permissions for Lambda functions.
- **GitHub Pages** - Hosts the frontend application for easy access.

## Installation and Setup

### Prerequisites
- **Node.js** and **npm** installed
- **AWS CLI** configured with permissions to deploy to Lambda
- **Docker** installed for containerizing backend code

### Frontend Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/online-ide.git
   cd online-ide
   ```
2. Install frontend dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Open http://localhost: in your browser to view the application.
   
   
### Backend Setup

-API Gateway for backend logic for compilation :
  ```bash
    https://3t3vy3oy01.execute-api.us-west-2.amazonaws.com/danish
  ```

### Preview

-Go to the link : 
   ```bash
      https://gleeful-squirrel-296a65.netlify.app/
   ```

### Screen Shot 
![IDE Interface](compiler-app/src/assets/IDE.png)


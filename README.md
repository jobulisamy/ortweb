# ONNX Runtime Web Training Demo

This project demonstrates on-device training using ONNX Runtime Web in a React application. It allows users to run training and testing epochs directly in the browser, visualizing training loss and test accuracy in real-time.

Code based on the official Microsoft ONNX Runtime training examples.

## Features

- On-device training using ONNX Runtime Web.
- Real-time visualization of training loss and test accuracy using Plotly.
- Configurable training parameters (batch size, epochs, etc.).
- Live logging of training and testing progress.
- Material UI for a clean and responsive interface.

## Technology Stack

- React
- ONNX Runtime Web (Training)
- Material UI (MUI)
- Plotly.js
- TypeScript
- Webpack

## Getting Started

### Prerequisites

Ensure you have Node.js and npm installed on your machine.

### Installation

1. Clone the repository.
2. Navigate to the project directory.
3. Install the dependencies:
   ```bash
   npm install
   ```

### Running Locally

To start the development server and run the application locally:

```bash
npm run start
```

The application will be available at `http://localhost:8080` (or the port specified by webpack-dev-server).

## Building for Production

To create a production build of the application:

```bash
npm run build
```

The build artifacts will be located in the `public` directory.

## Deployment

The project is configured for deployment to GitHub Pages:

```bash
npm run deploy
```

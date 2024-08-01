# Text Editor PWA

## Description

This project is a Progressive Web Application (PWA) text editor that allows users to create notes or code snippets with or without an internet connection, ensuring reliable data retrieval for later use. The application leverages IndexedDB for data persistence, making it possible to store content offline. The app is built using modern JavaScript, Webpack, and Workbox for service worker management, and is deployed on Render.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Installation

To get started with this project, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/text-editor-pwa.git
    cd text-editor-pwa
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

3. Build the project:
    ```sh
    npm run build
    ```

4. Start the development server:
    ```sh
    npm run start
    ```

## Usage

Once the server is running, you can access the application in your web browser at `http://localhost:3000`. The text editor allows you to write and save content. Your content is saved in IndexedDB and will be available even when you reload the page or go offline.

To install the PWA on your desktop or mobile device:

1. Open the application in your web browser.
2. Click on the "Install" button that appears on the screen.
3. Follow the prompts to add the application to your h

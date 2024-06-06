# Just Another Text Editor (J.A.T.E)

## Description

J.A.T.E (Just Another Text Editor) is a progressive web application (PWA) that allows you to create notes or code snippets with or without an internet connection. It provides a reliable and convenient way to store and retrieve your notes or code snippets for later use.
## Features

* Offline Functionality: The application can be used without an internet connection, thanks to the power of PWAs and service workers.
* Persistent Data Storage: Your notes or code snippets are automatically saved using IndexedDB, ensuring that your data is securely stored and can be retrieved even after closing and reopening the application.
* Bundled with Webpack: The application's JavaScript files are bundled using webpack, ensuring efficient and optimized code delivery.
* Next-Gen JavaScript Support: J.A.T.E supports the latest JavaScript features, allowing you to write modern and maintainable code without worrying about browser compatibility issues.
* Installable as a Desktop App: With the click of a button, you can install J.A.T.E as a desktop application, providing a seamless and native-like experience.
* Service Worker with Caching: The application utilizes a registered service worker with caching capabilities, ensuring faster load times and offline accessibility for static assets.

## Installation
To run J.A.T.E locally, follow these steps:

* Clone the repository: git clone https://github.com/your-username/jate.git
* Navigate to the project directory: cd jate
* Install dependencies: npm install
* Start the application: npm run start

## Usage

Open your web browser and navigate to http://localhost:3000 to access the J.A.T.E application.
Start typing your notes or code snippets in the text editor.
Your content will automatically be saved using IndexedDB as you type or click outside the editor.
To install the application as a desktop app, click the "Install" button.
If you close and reopen the application, your previously saved content will be retrieved from IndexedDB.

## Technologies Used

* JavaScript
* Node.js
* Express.js
* Webpack
* Workbox
* IndexedDB
* Progressive Web Application (PWA)

## Contributing
Contributions to J.A.T.E are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
[Visit my GitHub profile](https://github.com/14jjfenlason)

## License
This project is licensed under the MIT License.

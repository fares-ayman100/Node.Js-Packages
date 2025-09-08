# Node.Js-Packages
## First Step To Initialize NPM In the Project Use command

| #  | Package   | Description |
|----|-----------|-------------|
| 1  | **fs**        | A **core Node.js module for interacting with the file system**: reading, writing, editing, and deleting files. |
| 2  | **http**      | A **core Node.js module for creating servers** and handling HTTP protocol directly. |
| 3  | **lodash**    | A utility library for working with arrays, objects, and strings. **Provides functions** for sorting, searching, deep cloning, merging, etc. |
| 4  | **nodemon**   | A tool that **automatically restarts the server** whenever you make changes to the code. |
| 5  | **commander** | A library that simplifies **building command-line interfaces (CLI)** and handling commands and options. |
| 6  | **inquirer**  | A library for **creating interactive prompts in the terminal**. Useful for **CLI apps to ask the user questions** (yes/no, choices, text input). |
| 7  | **express**   | A lightweight **framework built on top of Node.js** for **creating web servers and APIs** using routes and middleware. |
| 8  | **morgan**    | A middleware for Express that **logs HTTP requests**. It **shows the request method**, **requested URL**, and **response time** in the console. |
| 9  | **mongodb**    | The official Node.js driver for MongoDB. It gives direct, **low-level access to the database** with no abstraction layer, **allowing full control over queries and operations**. |
| 10  | **mongoose**    | An ODM **(Object Data Modeling)** library for MongoDB and Node.js. **It provides schemas, models, and validation**, **making it easier to work with MongoDB in a structured way**. |
| 11 | express-validator | A set of **express.js middlewares**that validate and sanitize incoming request data. |
| 12 | dotenv          | Loads environment variables from a `.env` file into `process.env` for **secure configuration management.** |
| 13 | cors            | A middleware that enables Cross-Origin Resource Sharing (CORS) to allow or **restrict requested resources on a web server.** |
| 14 | validator       | A library for **string validation and sanitization** (e.g., checking emails, URLs, UUIDs). |
| 15 | bcrypt          | A library for **hashing and comparing passwords** using the bcrypt algorithm.   |
| 16 | bcryptjs        | A **pure JavaScript implementation of bcrypt** (works without native dependencies). |
| 17 | jsonwebtoken    | A library to **create, sign, and verify JSON Web Tokens (JWT) for authentication and authorization.** |
| 18 | multer          | A middleware for handling `multipart/form-data`, **mainly used for file uploads** in Node.js. |
| 19 | socket.io       | A library that **enables real-time, bidirectional communication** between clients and servers over WebSockets. |








### تثبيت أدوات التحقق من الكود (Linting & Formatting)

لتثبيت الأدوات الخاصة بالـ linting و formatting للكود، استخدم الأمر التالي:

```bash
npm install eslint prettier eslint-config-prettier eslint-plugin-prettier eslint-config-airbnb eslint-plugin-node eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-react --save-dev --legacy-peer-deps

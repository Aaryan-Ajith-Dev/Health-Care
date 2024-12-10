
# HealthCare Platform

## Description
A full-stack telehealth platform designed to redefine the landscape
of remote medical consultations. The goal is to create an integrated system employing chats, and audio/video calls that connect patients with appropriate virtual/live medical consultants.

## Environment Variables

The backend is built using **express** and **node.js** and is hosted on: 
```plaintext
https://localhost:PORT
```
The frontend is the **Vite + React** app which is hosted on:
```plaintext
https://localhost:5173
```
To run this project, you will need to add the following environment variables to your .env file

`DB` (Should have a MongoDB account, create a cluster then add the URL given)

`SECRET_ACCESS_TOKEN`    (Any random number works)

`PORT` (Contains port number for backend server)




## Run Locally

This app is built using Node.js and Express. So you need to have those installed.

### Install Node.js:

1. **Download Node.js:**
    Visit the official Node.js website at [https://nodejs.org/](https://nodejs.org/) and download the latest LTS version for your operating system.

2. **Install Node.js:**
    Follow the installation instructions provided on the Node.js website for your specific operating system.

3. **Verify Installation:**
    Open a terminal or command prompt and run the following commands to verify that Node.js and npm (Node Package Manager) are installed successfully:
    ```bash
    node -v
    npm -v
    ```
    These commands should display the installed Node.js version and the npm version.

### Install Express:

Once Node.js is installed, you can use npm to install Express globally.

On your terminal or command prompt run the following command:

```bash
npm install -g express
```
### Then

Clone the project

```bash
  git clone https://github.com/sohith18/Health-Care.git
```

Go to the project directory

```bash
  cd Health-Care
```
Run the like this:

- Go to the client directory

  ```bash
    cd client
  ```

- Install dependencies by using
  ```bash
    npm install
  ```
- Start the front-end server:
  ```bash
    npm run dev
  ```
Run the server like this:

- Go to the server directory

  ```bash
    cd server
  ```

- Install dependencies by using
  ```bash
    npm install
  ```
- Finally
  ```bash
    npm start
  ``` 
  should fire the backend server.



## Authors

- Aaryan Dev [Aaryan-Ajith-Dev](https://github.com/Aaryan-Ajith-Dev)
- Shreyas S [@Shreyas0S](https://www.github.com/Shreyas0S)
- Sohith [@sohith18](https://github.com/sohith18)
- Siddharth Reddy [@siddharthmaram](https://github.com/siddharthmaram)

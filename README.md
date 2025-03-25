## Guide to Install and Run React Project

This guide will walk you through the steps to install the necessary dependencies and run your React project, "react-native-project," based on the instructions provided in your README.

**Prerequisites:**

* **Node.js and npm (Node Package Manager):** Ensure you have Node.js and npm installed on your system. You can download and install them from the official Node.js website (nodejs.org).

**Steps:**

**1. Install Environment (Dependencies):**

   * Open your terminal or command prompt.
   * Navigate to the root directory of your project, "react-native-project," using the `cd` command. For example:

     ```bash
     cd /path/to/your/react-native-project
     ```

   * Execute the following command to install all the project dependencies listed in the `package.json` file:

     ```bash
     npm install
     ```

     or

     ```bash
     npm i
     ```

     This command will download and install all the required packages into the `node_modules` folder within your project directory. This process may take some time depending on your internet connection and the number of dependencies.

**2. Run Project:**

   * Once the installation is complete, execute the following command to start the development server:

     ```bash
     npm run dev
     ```

   * This command will trigger the script defined as "dev" in your `package.json` file. Typically, it will start a development server that watches for file changes and automatically refreshes your browser.
   * After the command runs, the terminal should display an address where the react application is running. Usually it is "localhost" with a port number, for example: http://localhost:5173/
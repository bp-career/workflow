# Workflow Project Setup Guide

Welcome to the **Workflow** project! This guide will walk you through the steps of setting up the current version of the project on your local machine. We’ll cover everything you need to do to get up and running, including folder setup, software installation, and starting the project.

## Step-by-Step Instructions

### 1. Create Folders on Your Local Machine
Before you start, you need to set up the correct folder structure on your local machine.

1. **Create a folder called `Projects`**:
   - Navigate to a location on your computer where you'd like to store your projects (e.g., Documents or Desktop).
   - Create a new folder and name it `Projects`.

2. **Create a folder called `workflow` inside the `Projects` folder**:
   - Inside the `Projects` folder, create another folder named `workflow`.

### 2. Install Visual Studio Code (VS Code)

You’ll need Visual Studio Code (VS Code) to work with the code and open a terminal for running commands.

1. Download and install **[Visual Studio Code](https://code.visualstudio.com/)**.
   - Follow the installation instructions based on your operating system (Windows, macOS, or Linux).
   
2. Once installed, **open the `workflow` folder**:
   - Open VS Code.
   - From the **File** menu, select **Open Folder** and choose the `workflow` folder you just created inside `Projects`.

### 3. Install Required Software: Node.js

Before running the project, you need to install **Node.js**, which is required to run the development server.

#### How to Install Node.js:

1. Go to the official **[Node.js website](https://nodejs.org/)**.
2. Download the **LTS (Long Term Support)** version, which is the recommended version for most users.
3. Run the installer and follow the instructions.
   - After installation, you can verify Node.js and npm (Node Package Manager) are installed correctly by opening a terminal and typing:
     ```bash
     node -v
     npm -v
     ```
   - This should return the version numbers of Node.js and npm. If you see the versions, you're good to go!

### 4. Add the Project with ShadCN CLI Tool

1. Open the **Terminal** in VS Code:
   - In VS Code, go to the **Terminal** menu and select **New Terminal** to open the integrated terminal.

2. Run the following command in the terminal:
   ```bash
   npx shadcn@latest add "https://v0.dev/chat/b/osdYAOj2mvP?token=eyJhbGciOiJkaXIiLCJlbmMiOiJBMjU2R0NNIn0..GjNVCyPWE0PlnVtb.MR1exnNWr5883_RlhAXxcXi4e8XdSjtQ4DBEtbgcb-MXW_zmU0VyFLoH.yg4CAzqWynMr2N_DzLhmSA"
   ```

3. The command will prompt you to confirm by typing `y` and hitting **Enter**:
   - When prompted, type `y` and press **Enter** to proceed.

4. Continue pressing **Enter**:
   - You may be asked to confirm a few additional times. Keep pressing **Enter** to accept the default choices.

### 5. Navigate to Your App and Start the Development Server

1. **Navigate to the app folder**:
   - After the setup finishes, type the following command in the terminal to go to the newly created app directory:
     ```bash
     cd my-app
     ```

2. **Start the development server**:
   - To start the app locally, type the following command and press **Enter**:
     ```bash
     npm run dev
     ```

3. The terminal will display the local server URL (usually something like `http://localhost:3000/`).

### 6. Open the Project in Your Browser

1. Open **Google Chrome** (or your preferred browser).
2. Copy and paste the local domain URL from the terminal into the browser’s address bar (e.g., `http://localhost:3000/`).
3. Your project should now be up and running in the browser.

---

## Troubleshooting Tips

- **If you encounter any issues with Node.js**, ensure you have the latest version installed and that it’s properly set up on your system.
- **If the `npx` command fails**, double-check that you have an active internet connection and that you typed the URL correctly.

---

## Conclusion

You’ve successfully set up and started the **Workflow** project on your local machine! If you encounter any issues or have questions, please reach out to your technical support team or refer to the documentation provided with the project. Enjoy working with **Workflow**!

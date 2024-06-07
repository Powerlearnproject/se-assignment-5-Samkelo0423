[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15236165&assignment_repo_type=AssignmentRepo)

### Installation of VS Code

**Steps to Download and Install VS Code on Windows 11:**

1. **Download VS Code:**
   - Go to the official Visual Studio Code website: [code.visualstudio.com](https://code.visualstudio.com/).
   - Click on the "Download for Windows" button.

2. **Install VS Code:**
   - Once the download is complete, open the downloaded `.exe` file.
   - Follow the installation wizard:
     - Accept the agreement.
     - Choose the installation location.
     - Select additional tasks (creating a desktop icon, adding to PATH, etc.).
   - Click "Install" to complete the installation.

**Prerequisites:**
   - Windows 11 operating system.
   - Administrator privileges for installation.

### First-time Setup

**Initial Configurations and Settings:**

1. **User Settings:**
   - Open VS Code.
   - Go to `File` > `Preferences` > `Settings` or use the shortcut `Ctrl + ,`.
   - Customize settings such as theme, font size, auto-save, etc.

2. **Extensions:**
   - Click on the Extensions view icon on the Sidebar or press `Ctrl + Shift + X`.
   - Install essential extensions, for example:
     - **Python** (for Python development)
     - **Prettier - Code formatter** (for code formatting)
     - **ESLint** (for JavaScript linting)
     - **Live Server** (for a quick local development server)

3. **Theme and Icon Pack:**
   - Install preferred themes like "One Dark Pro" or "Dracula".
   - Optionally, install icon packs like "Material Icon Theme".

### User Interface Overview

**Main Components of VS Code UI:**

1. **Activity Bar:**
   - Located on the left side, it provides access to different views like Explorer, Search, Source Control, Run and Debug, and Extensions.

2. **Side Bar:**
   - Displays the content related to the selected view in the Activity Bar, such as file explorer, search results, or extension details.

3. **Editor Group:**
   - The main area where files are opened and edited. Multiple editors can be opened side by side.

4. **Status Bar:**
   - Located at the bottom, it provides information about the current file, errors, warnings, and background processes. It also includes shortcuts to language modes, encoding, and line endings.

### Command Palette

**Command Palette:**

- **Accessing Command Palette:**
  - Use the shortcut `Ctrl + Shift + P` or `F1`.

- **Common Tasks:**
  - **Search and install extensions:** Type `ext install`.
  - **Change theme:** Type `Preferences: Color Theme`.
  - **Run code snippets:** Type the snippet keyword and execute.
  - **Git commands:** Type `Git: ...` for Git-related actions.

### Extensions in VS Code

**Role of Extensions:**

- Extensions enhance VS Code by adding functionality such as language support, themes, debuggers, and tools.

**Finding, Installing, and Managing Extensions:**

1. **Find and Install:**
   - Open the Extensions view (`Ctrl + Shift + X`).
   - Search for the desired extension and click "Install".

2. **Manage Extensions:**
   - Access installed extensions from the Extensions view.
   - Disable, uninstall, or update extensions as needed.

**Essential Extensions for Web Development:**
- **HTML, CSS, and JavaScript:** Built-in support.
- **Prettier - Code Formatter:** Ensures consistent code formatting.
- **ESLint:** Identifies and fixes problems in JavaScript code.
- **Live Server:** Provides a local development server with live reload.

### Integrated Terminal

**Opening and Using Integrated Terminal:**

- **Open Integrated Terminal:**
  - Use the shortcut `Ctrl + ` (backtick) or go to `View` > `Terminal`.

- **Advantages:**
  - Direct access to a command-line interface within VS Code.
  - Simplifies running scripts, managing version control, and executing commands without leaving the editor.

### File and Folder Management

**Creating, Opening, and Managing Files and Folders:**

1. **Create:**
   - Right-click in the Explorer view and select `New File` or `New Folder`.
   - Use the shortcut `Ctrl + N` to create a new file.

2. **Open:**
   - Use `File` > `Open Folder` or `Ctrl + O` to open an existing folder.
   - Use `File` > `Open File` to open a specific file.

3. **Manage:**
   - Navigate using the Explorer view.
   - Use `Ctrl + P` to quickly open files by name.
   - Split the editor using `Ctrl + \`.

### Settings and Preferences

**Customizing Settings:**

- **Access Settings:**
  - Go to `File` > `Preferences` > `Settings` or use `Ctrl + ,`.

- **Change Theme:**
  - Search for `Color Theme` in the Command Palette (`Ctrl + Shift + P`).

- **Adjust Font Size:**
  - Search for `Editor: Font Size` in Settings.

- **Modify Keybindings:**
  - Go to `File` > `Preferences` > `Keyboard Shortcuts` or use `Ctrl + K, Ctrl + S`.

### Debugging in VS Code

**Setting Up and Starting Debugging:**

1. **Open the Debug View:**
   - Click the Debug icon in the Activity Bar or use `Ctrl + Shift + D`.

2. **Configure Debugger:**
   - Click on `create a launch.json file` link to configure your debugger.
   - Select the appropriate environment (e.g., Node.js, Python).

3. **Start Debugging:**
   - Set breakpoints by clicking in the gutter next to the line numbers.
   - Click the green play button or press `F5` to start debugging.

**Key Debugging Features:**
   - Breakpoints, watch variables, call stack, and stepping through code.

### Using Source Control

**Integrating Git with VS Code:**

1. **Initialize Repository:**
   - Open the Source Control view by clicking the Git icon in the Activity Bar or using `Ctrl + Shift + G`.
   - Click `Initialize Repository`.

2. **Making Commits:**
   - Stage changes by clicking the `+` icon next to changed files.
   - Enter a commit message and click the checkmark to commit.

3. **Pushing to GitHub:**
   - Open the Command Palette (`Ctrl + Shift + P`), type `Git: Add Remote`, and add your repository URL.
   - Use the Command Palette to `Git: Push` to the remote repository.

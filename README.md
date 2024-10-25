# Mise GUI

This repository provides a graphical user interface (GUI) for the [Mise](https://github.com/jdx/mise) CLI tool, allowing users to easily manage and interact with their web development projects without needing to use the command line.

## Features

- Cross-platform GUI for **Linux**, **macOS**, and **Windows**.
- Full integration with the **Mise** CLI, offering the same functionality in an intuitive graphical format.
- Easy project creation, management, and configuration.
- Visual feedback for command execution, logs, and errors.
- User-friendly design for both beginners and advanced developers.

## Prerequisites

Before you can use this tool, you need to have the following installed on your system:

1. **Mise CLI**
   - Follow the installation instructions from the [Mise repository](https://github.com/jdx/mise).
   
2. **Node.js** (if using Electron).

## Installation

### Electron (JavaScript/Node.js)

1. Clone this repository:

    ```bash
    git clone https://github.com/yourusername/mise-gui.git
    cd mise-gui
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Run the app:

    ```bash
    npm start
    ```

4. To package the application for your platform:

    ```bash
    npm run build
    ```

### Python + PyQt5

1. Clone this repository:

    ```bash
    git clone https://github.com/yourusername/mise-gui.git
    cd mise-gui
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the app:

    ```bash
    python main.py
    ```

4. To package the app for distribution, use:

    ```bash
    pyinstaller --onefile --windowed main.py
    ```

## Usage

Once the application is running, you can use the GUI to perform the following actions:

- **Create a new project**: Start a new Mise project with a simple form input.
- **Manage existing projects**: Easily navigate through and manage multiple projects.
- **Configure settings**: Modify project settings via graphical menus instead of manually editing configuration files.
- **Run commands**: Execute Mise commands (e.g., `mise run`, `mise build`) with a click, and see output logs and errors in real time.

## Screenshots

_Coming soon_

## Contributing

We welcome contributions! If you would like to contribute, please fork the repository and submit a pull request with your changes. Issues and feature requests are also appreciated.

### Steps to contribute:

1. Fork this repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

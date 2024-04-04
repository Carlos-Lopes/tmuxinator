# Tmuxinator Configuration Repository

---

## Description

This repository serves as a central location for storing configuration files for [Tmuxinator](https://github.com/tmuxinator/tmuxinator), a tool designed to manage complex tmux sessions easily. Tmuxinator allows users to define and manage tmux sessions with a simple YAML configuration file.

## Usage

1. **Clone the Repository:**

    ```
    git@github.com:Carlos-Lopes/tmuxinator.git
    ```

2. **Install Tmuxinator:**

    If you haven't already installed Tmuxinator, you can do so by following the instructions on the [official Tmuxinator repository](https://github.com/tmuxinator/tmuxinator).

3. **Customize Configuration:**

    Edit the `.yml` files in the repository to match your desired tmux session setups. You can create new files or modify existing ones according to your preferences.

4. **Create Sessions:**

    Use Tmuxinator to create sessions based on the configurations defined in the `.yml` files. For example:

    ```
    tmuxinator start session_name dir_path
    ```

    Replace `session_name` with the name of the session configuration you want to start.
   
    Replace `dir_path` with the path the session should start.

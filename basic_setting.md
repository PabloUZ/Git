# Basic Settings
## Install Git
- Windows:
    1. Download [INSTALLER](https://git-scm.com/) for windows
    2. Execute without changing any configuration.
    3. Search in app menu for "Git Bash", it should open a command prompt
- Mac:
    1. Download [INSTALLER](https://git-scm.com/) for mac
    2. Execute without changing any configuration.
    3. Open terminal and execute:
    ```bash
    git --version
    ```
- Linux: 

    Open terminal and execute:
    - Debian-based:
        ```bash
        sudo apt install git
        ```
    - Arch-based:
        ```bash
        sudo pacman -S git
        ```

## Git global settings

> Set user name<br>
>```bash
>git config --global user.name "<NAME>"
>```

> Set user email (must be the same as github for compatibility)<br>
>```bash
>git config --global user.email "<EMAIL>"
>```

> Set default branch<br>
>```bash
>git config --global init.defaultBranch main
>```
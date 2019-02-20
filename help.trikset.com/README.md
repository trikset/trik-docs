# Setup environment

## GNU/Linux or macOS

    In `bash`/`zsh` or `fish` shell it is like
    ```shell
        python3 -m virtualenv --clear -p python3  -v venv
        source venv/bin/activate # source corresponding activate.XXX for your shell
        python -m pip install --upgrade pip
        pip install --upgrade sphinx
    ```

## Windows

    use Windows Subshell for Linux (WSL) or install Python 3.x and use `pip` to install fresh `sphinx` module. But using of virtual environment is strongly advised.  

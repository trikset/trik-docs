# Setup environment

## GNU/Linux or macOS

    In `bash`/`zsh` or `fish` shell it is like
    ```shell
        python3 -m virtualenv --clear -p python3  -v venv
        source venv/bin/activate # source corresponding activate.XXX for shell other than bash/zsh
        pip install -Ur requirements.txt
    ```

## Windows

    Use Windows Subshell for Linux (WSL) or install Python 3.x and use `pip -Ur requirements.txt`, or use your favorite Python IDE to install requirements. But using of virtual environment is strongly advised.

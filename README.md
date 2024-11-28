<p align="center">
  <a href="https://haruyukis.github.io/sora/" target="_blank">
    <img alt="" src="./docs/logo.png?raw=true" width="150" style="max-width: 100%;">
  </a>
</p>

<p align="center">
  SORA - Japanese Speech-Oriented Recognition and Assistance
</p>

<p align="center">
  <img src="https://img.shields.io/badge/License-Private-red.svg" alt="Private">
  <!--
  <a href="https://github.com/haruyukis/sora/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/haruyukis/sora" alt="License">
  </a>
  -->
</p>

---

## Contribution

### Installation

Please install [VSCode](https://code.visualstudio.com/) and its extensions:

- Python
- Pylance
- Black Formatter
- isort
- Even Better TOML
- Prettier
- Git Graph
- vscode-pdf
- One Dark Pro (optional)
- Material Icon Theme (optional)

Please install [git](https://git-scm.com/download/linux):

```bash
sudo apt install git
```

## Backend

Please install [Python](https://www.python.org/downloads/).

```bash
sudo apt install python3 python3-pip python3-venv
```

Please install [Poetry](https://python-poetry.org/docs/#installing-with-the-official-installer):

```bash
curl -sSL https://install.python-poetry.org | python3 -
if ! command -v poetry &> /dev/null; then
  echo '\n# Poetry\nexport PATH=$HOME/.local/bin:$PATH' >> $HOME/.bashrc
  source $HOME/.bashrc
else
  echo "Poetry already added to PATH."
fi
poetry config virtualenvs.in-project true
```

To create your Python environment and install dependencies:

```bash
poetry install
```

Please reload the VSCode window:

- In VSCode, press `CTRL + SHIFT + P`
- Click on `Developer: Reload Window`

If all worked, congratulations! You are ready to contribute!

### Commands

To launch:

```bash
poetry run python main.py
```

To update dependencies:

```bash
poetry update
```

### Other commands

To clear poetry cache:

```bash
poetry cache clear --all .
```

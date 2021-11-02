## Install Dev Env (ubuntu 20.04)

- `sudo apt install zsh`
- `sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`

- `sudo apt install python3.9 python3.9-venv python3-pip`
- `python3.9 -m venv .venv`
- `curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/install-poetry.py | python3 -`
- `printf "\n"'export PATH="$HOME/.local/bin:$PATH"' >> ~/.zshrc && source ~/.zshrc`
- `poetry run pip install --upgrade pip`
- `poetry install`

- `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash`
- Restart terminal, then `nvm install --lts`

- `npm install -g yarn`

install docker-compose

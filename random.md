## Fixes:
- Keychron keyboard fn keys fix (linux)
```console
echo "options hid_apple fnmode=0" | sudo tee -a /etc/modprobe.d/hid_apple.conf
```

## pyenv
https://github.com/pyenv/pyenv/wiki#suggested-build-environment

brew install pyenv
echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.zshrc
echo '[[ -d $PYENV_ROOT/bin ]] && export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.zshrc
echo 'eval "$(pyenv init -)"' >> ~/.zshrc

MacOS
xcode-select --install
brew install openssl readline sqlite3 xz zlib tcl-tk

debian like

sudo apt update; sudo apt install build-essential libssl-dev zlib1g-dev \
libbz2-dev libreadline-dev libsqlite3-dev curl \
libncursesw5-dev xz-utils tk-dev libxml2-dev libxmlsec1-dev libffi-dev liblzma-dev 


poetry install 3.11

sudo apt install python3.12-distutils python3.12-venv python3.12-dev python3-pip
    
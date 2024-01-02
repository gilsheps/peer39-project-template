# Install Python and Poetry

## Install Homebrew 
Use this if you need to install Python

Command to install brew
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Once you have Homebrew installed, to get python3, just run:
```bash
brew install python3
```

## Install Poetry
Run this command in order to install poetry 
```bash
curl -sSL https://install.python-poetry.org | python3 -
```

## Run Poetry to install in order to install dependencies
```bash
poetry install
```

## Add your own dependencies to project
Open project.toml file and add dependency under tool.poetry.dependencies section


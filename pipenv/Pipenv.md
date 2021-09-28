# Pipenv

## Install pipenv
```zsh
# Install pipenv
pip3 install pipenv
```

## Module
```zsh
# Install python module
pipenv install <Module>
pipenv install -r requirement.txt

# Uninstall python module
pipenv uninstall <Module>
pipenv uninstall -r requirement.txt
```

## Virtual Enviroment
```zsh
# Create python virtual env
pipenv --python <Version>
  
# Run a single program(Don't enter the virtual env)
pipenv run python <Filename>

# Enter the virtual env
pipenv shell
```

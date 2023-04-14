
가상환경 설치 방법

brew update
brew install pyenv
brew install pyenv-virtualenv

pyenv versions 
pyenv install --list
pyenv install <version-you-want>
pyenv uninstall <version-you-want>

vi ~/.bashrc

export PATH="$HOME/.pyenv/bin:$PATH" 
eval "$(pyenv init -)" 
eval "$(pyenv virtualenv-init -)"

exec $SHELL

pyenv local <version-you-want>
pyenv global <version-you-want>


 pip install django
django-admin startproject config .
django-admin startapp app

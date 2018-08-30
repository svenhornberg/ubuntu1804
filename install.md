# PostInstall Ubuntu 1804

## Update
    sudo apt-get update
    sudo apt-get upgrade

## Python

    sudo apt-get install python3-venv 
    sudo ln -s /usr/bin/python3 /usr/bin/python
 
    # Danach venv benutzen https://docs.python.org/3/tutorial/venv.html
            python3 -m venv .
            source bin/activate
            pip install pip --upgrade

## Docker-CE

    sudo addgroup --system docker
    sudo adduser $USER docker
    newgrp docker
    
    snap install docker
    

    sudo apt install docker-compose #TODO: installiert python2 


log in & log out

## Visual Studio Code

https://snapcraft.io/vscode
    
    sudo snap install vscode --classic
    
    Extensions: Gitlens 
## Other

    sudo snap install node --channel=10/stable --classic
    sudo snap install aws-cli --classic
    
## TODO:
    https://github.com/robbyrussell/oh-my-zsh

# PostInstall Ubuntu 1804

## Update
    sudo apt-get update
    sudo apt-get upgrade

## Python
    sudo apt-get install python3-pip

    sudo ln -s /usr/bin/python3 /usr/bin/python
    sudo ln -s /usr/bin/pip3 /usr/bin/pip
    
    sudo apt-get install python3-mysqldb
    

## Docker-CE

https://docs.docker.com/install/linux/docker-ce/ubuntu/#install-docker-ce

    sudo apt-get update


    sudo apt-get install \
      apt-transport-https \
      ca-certificates \
      curl \
      software-properties-common


    curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
    
    
    sudo add-apt-repository \
     "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
     $(lsb_release -cs) \
     stable"

    sudo apt-get update

    sudo apt-get install docker-ce

    sudo usermod -aG docker $USER

    sudo apt install docker-compose


log in & log out

## Visual Studio Code

https://snapcraft.io/vscode
    
    sudo snap install vscode --classic
    
    Extensions: Gitlens 
## Other

    sudo snap install node --channel=10/stable --classic
    sudo snap install aws-cli --classic

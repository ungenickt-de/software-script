# software-script

This repo containes several scripts to easily setup some basic services on your virtual server / VPS / dedicated server.

## Download the scripts / get the repo

**MAKE SURE YOU ARE LOGGED IN AS ROOT USER, OTHERWISE USE SUDO !**

Without git, use the following to download this repository 

    apt-get install wget unzip
    wget https://github.com/ungenickt-de/software-script/archive/master.zip && unzip master.zip && rm master.zip

If you have git installed, use 

    git clone https://github.com/ungenickt-de/software-script.git


Go into the folder and execute the script of your choice, e.g.

    cd software-script* && ./bedrock_server.sh

    cd software-script* && ./jenkins.sh

    cd software-script* && ./minecraft_server.sh

    cd software-script* && ./mysql_server.sh

    cd software-script* && ./teamspeak.sh

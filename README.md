# python3.8_install_guide_-virtualenv

<center>
<a href="https://www.buymeacoffee.com/atulkumar6556" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>
<a href="https://forum.arduino.cc/u/atulkumar6556" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/87/Arduino_Logo.svg/1280px-Arduino_Logo.svg.png" alt="Arduino " style="height: 60px !important;width: 217px !important; " ></a>
<a href="https://forum.boltiot.com/u/atulkumar6556/" target="_blank"><img src="https://i0.wp.com/atlanta.makerfaire.com/wp-content/uploads/sites/9/gravity_forms/16-172723c9d9294ab43c7a992c8f41d157/2018/09/Bolt_MakerFaire.png?fit=750%2C500&strip=all   " alt="Boltiot" style="height: 60px !important;width: 217px !important;"  border-radius: 20%></a>
</center>

## Install python 3.8 

### (1)
    sudo apt update
### (2)
    sudo apt install build-essential zlib1g-dev libncurses5-dev libgdbm-dev libnss3-dev libssl-dev libreadline-dev libffi-dev libsqlite3-dev wget libbz2-dev
### (3)
    wget https://www.python.org/ftp/python/3.8.0/Python-3.8.0.tgz
### (4)
    tar -xf Python-3.8.0.tgz
### (5)
    cd Python-3.8.0
### (6)
    ./configure --enable-optimizations
### (7)
    make -j 8
### (8)
    sudo make altinstall
### (9)
    python3.8 --version

#  TO Make Virtual Environment install ----
### (1)
    sudo apt-get install python-virtualenv
### (2)
    virtualenv --python=/usr/local/bin/python3.8 your_venvname

### ACTIVATE YOUR VIRTUALENV USING --

### (1)
      cd YOUR_VIRTUALENV_PATH_
      
### (2)
      source yourvirtualenvname/bin/activate
      
      
--------------------------------------------------------------------------------   
                  
                                                                                                          ### IOT DEVELOPER
                                                                                                          ## ATUL KUMAR

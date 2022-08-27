# python3.8_install_guide_-virtualenv
https://forum.arduino.cc/u/atulkumar6556
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

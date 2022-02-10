# python3.8_install_guide_-virtualenv
<h1>Install python 3.8</>


sudo apt update

sudo apt install build-essential zlib1g-dev libncurses5-dev libgdbm-dev libnss3-dev libssl-dev libreadline-dev libffi-dev libsqlite3-dev wget libbz2-dev

wget https://www.python.org/ftp/python/3.8.0/Python-3.8.0.tgz

tar -xf Python-3.8.0.tgz

cd Python-3.8.0

./configure --enable-optimizations

make -j 8

sudo make altinstall

python3.8 --version

#  TO Make Virtual Environment install ----

sudo apt-get install python-virtualenv

virtualenv --python=/usr/local/bin/python3.8 your_venvname

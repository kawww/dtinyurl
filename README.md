# dtinyurl
Dcentralised url shortening service base on ipfs


### Demo

http://t.bdaily.club


install ipfs https://docs.ipfs.io/guides/guides/install/#installing-with-ipfs-update

use pip3

sudo apt-get install python3
sudo apt install python3-pip

sudo update-alternatives --install /usr/bin/python python /usr/bin/python2 100
sudo update-alternatives --install /usr/bin/python python /usr/bin/python3 150

 
python --version



### Run

    1. ipfs daemon
    
    2. pip install -r requirements.txt
    
    3. python manage.py runserver


1 * * * * /usr/local/bin/ipfs daemon 
@reboot python3 /home/manage.py runserver ip:80 --insecure

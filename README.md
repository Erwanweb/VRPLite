# VRPLite
install :

cd ~/domoticz/plugins

mkdir VRPLite

sudo apt-get update

sudo apt-get install git

git clone https://github.com/Erwanweb/VRPLite.git VRPLite

cd VRPLite

sudo chmod +x plugin.py

sudo /etc/init.d/domoticz.sh restart

Upgrade :

cd ~/domoticz/plugins/VRPLite

git reset --hard

git pull --force

sudo chmod +x plugin.py

sudo /etc/init.d/domoticz.sh restart

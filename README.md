# InstallTheos
 A quick script to install Theos on Linux/WSL

# Run this code:
1. sudo bash -c "$(wget -O - https://raw.githubusercontent.com/c939984606/InstallTheos/master/installtheos.sh)"
2. vi ~/.profile add:  

   export PATH=/opt/theos/bin/:$PATH
   PATH=$PATH:$HOME/bin:/opt/theos/bin

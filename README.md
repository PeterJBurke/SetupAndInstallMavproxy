# SetupAndInstallMavproxy
Install mavproxy after setting up linux machine.
Using instructions here:
https://ardupilot.org/mavproxy/docs/getting_started/download_and_installation.html


# CreateSITLenv
Script to create SITL setup on Linux.

To run: 
 ```
sudo apt-get install curl -y;
curl https://raw.githubusercontent.com/PeterJBurke/SetupAndInstallMavproxy/main/setup.sh > ~/setup.sh;
chmod 777 ~/setup.sh;
bash ~/setup.sh;
```
To run for no GUI option:
To run: 
 ```
sudo apt-get install curl -y;
curl https://raw.githubusercontent.com/PeterJBurke/SetupAndInstallMavproxy/main/setupnogui.sh > ~/setupnogui.sh;
chmod 777 ~/setupnogui.sh;
bash ~/setupnogui.sh;
```


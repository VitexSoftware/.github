## Hi there 👋

[![wakatime](https://wakatime.com/badge/user/5abba9ca-813e-43ac-9b5f-b1cfdf3dc1c7.svg)](https://wakatime.com/@5abba9ca-813e-43ac-9b5f-b1cfdf3dc1c7)

Please copy & paste to your terminal:

```shell	    
sudo apt install lsb-release wget apt-transport-https bzip2


wget -qO- https://repo.vitexsoftware.com/keyring.gpg | sudo tee /etc/apt/trusted.gpg.d/vitexsoftware.gpg
echo "deb [signed-by=/etc/apt/trusted.gpg.d/vitexsoftware.gpg]  https://repo.vitexsoftware.com  $(lsb_release -sc) main" | sudo tee /etc/apt/sources.list.d/vitexsoftware.list
sudo apt update

sudo apt install package(s)
```
![apt get](https://www.vitexsoftware.com/img/thelaststudent.png)

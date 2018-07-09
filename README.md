# SoftEther Autoinstaller

This is my SoftEther autoinstaller. This will compile and install SoftEther onto your server. This installer in particular will set up SoftEther as a system service. Currently Ubuntu and CentOS are supported.

## Ubuntu
### 64-bit
`wget -O install https://raw.githubusercontent.com/icoexist/softether-autoinstall/master/ubuntu/x64/se-install-ubuntu.bash && chmod 777 install && ./install`

### 32-bit
`wget -O install https://raw.githubusercontent.com/icoexist/softether-autoinstall/master/ubuntu/x86/se-install-ubuntu-x86.bash && chmod 777 install && ./install`

## CentOS
### 64-bit
`curl -o install https://raw.githubusercontent.com/icoexist/softether-autoinstall/master/centos/x64/se-install-centos.bash && chmod 777 install && ./install`
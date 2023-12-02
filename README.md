# Programming-Languages
Programming Languages Installation Scripts

Installation steps on Ubuntu / Debian
Connect to your server through ssh and copy and run the following command in the terminal

Server Preparation
```
sudo apt update -y && sudo apt upgrade -y && reboot
```
After Rebooting Server
```
sudo apt install -y curl && sudo apt install -y dialog
```

Languages Scripts Installer
```
sudo bash -c "$(curl -Lfo- https://raw.githubusercontent.com/Amir-Net/Programming-Languages/main/start.sh)"
```

For manual installation, copy and run the following command in the terminal.
```
sudo bash -c "$(curl -Lfo- https://raw.githubusercontent.com/Amir-Net/Programming-Languages/main/go.sh)"
```

Used Projects in this script 🙏
```
https://github.com/golang
```
You can donate to me through Plisio at ❤️

<a href="https://plisio.net/donate/f_9qcQRU" target="_blank"><img src="https://plisio.net/img/donate/donate_light_icons_color.png" alt="Donate Crypto on Plisio" width="240" height="80" /></a>

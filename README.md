# MY_Kali-Nethunter-Fixes


- gawk package
```sh
wget https://github.com/mrx7014/MY_Kali-Nethunter-Fixes/blob/master/gawk_5.0.1%2Bdfsg-1ubuntu0.1_arm64.deb;sudo dpkg -i gawk_5.0.1+dfsg-1ubuntu0.1_arm64.deb;sudo apt update
```

- libsigsegv2 package
```sh
wget https://github.com/mrx7014/MY_Kali-Nethunter-Fixes/blob/master/libsigsegv2_2.14-1_arm64.deb;sudo dpkg -i libsigsegv2_2.14-1_arm64.deb;sudo apt update
```

- resolve.conf
```sh
wget https://github.com/mrx7014/MY_Kali-Nethunter-Fixes/blob/master/resolv.conf /etc;sudo apt update
```

- To install burpsuite
```sh
sudo apt install which;sudo apt install burpsuite
```

- Change `_apt:x:65:` to `_apt:x:0:` in `/etc/passwd` To fix `apt update` issues

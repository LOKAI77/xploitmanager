
![Logo](https://dev.geoplayer.cz/uploads/xploit_logo.png)


# XPLOIT MANAGER

xploit is a versatile bash script that checks for the installation status of various hacking tools and installs them if necessary. It is designed to make tool management easier by ensuring you have the required tools installed on your system for vulnerability assesment, bugbounty and penetration testing.


## Authors

- [@LOKAI77](https://www.github.com/octokatherine)


## Features

- Check for installation of a prefered tool
- One click installation of tools from available list


## Installation

Clone xploitmanager with git

```bash
git clone https://github.com/LOKAI77/xploitmanager  
echo "export PATH=$PATH:~/xploitmanager" >> ~/.bashrc
source ~/.bashrc
```

## Usage/Examples
Check if katana is installed:

```bash
xploit -t katana
```

Install katana if missing:

```bash
xploit -i katana
```

List available tools for installation/check:

```bash
xploit -l
```

Run all checks:

```bash
xploit -a
```


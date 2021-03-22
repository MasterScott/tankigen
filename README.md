# tankigen
![trial](assets/tankigen.gif)
reverse shells based on [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Reverse%20Shell%20Cheatsheet.md) and [Pentestmonkey](http://pentestmonkey.net/cheat-sheet/shells/reverse-shell-cheat-sheet) reverse shell cheat sheets.

Using this script you can easily generate various types of reverse shells without leaving your command line. This script will come in handy when you are playing [CTF](https://en.wikipedia.org/wiki/Capture_the_flag#Computer_security) like challenges.   


## Available Shell Types
- Bash
- Perl
- Ruby
- Golang
- Netcat
- Ncat
- Powershell
- Awk
- Lua
- Java
- Socat
- Nodejs
- Telnet
- Python

## Git Installation
```
# clone the repo
$ git clone https://github.com/thelinuxuser-choice/tankigen
# change the working directory to tankigen
$ cd tankigen
#install the requirements 
$pip install -r requirements.txt
#fire it up
$python3 tankigen.py
```

## Usage

```
usage: tankigen.py [-h] [-i IPADDR] [-p PORTNUM] [-t TYPE] [-l] [-a]
optional arguments:
  -h, --help            show this help message and exit
  -i IPADDR, --ip IPADDR
                        IP address
  -p PORTNUM, --port PORTNUM
                        Port number
  -t TYPE, --type TYPE  Type of the reverse shell to generate
  -l, --list            List all available shell types
  -a, --all             Generate all the shells
  
```
## screenshot


<p align='left'>
    <img src = '/assets/scr1.png' height="200" width = '500' >
<p align='right'>
    <img src = '/assets/scr2.png' height="200" width = '500' >
</p>
</p>






## Support & Contributions
- Please ⭐️ this repository if this project helped you!
- Contributions of any kind welcome!

## References
[Payloads All The Things Reverse Shell Cheat Sheet](https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Reverse%20Shell%20Cheatsheet.md)

[Pentestmonkey Reverse Shell Cheat Sheet](http://pentestmonkey.net/cheat-sheet/shells/reverse-shell-cheat-sheet)

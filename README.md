# ping
separate ping utility from iputils-s20151218.tar.gz which site http://www.skbuff.net/iputils/

### lib dependency
    sudo apt-get install libcap-dev

### make
    make

# If you are not root, like this: 
    xxx@xxx-pc:~/Documents/ping$ ./ping www.baidu.com
    ping: icmp open socket: Permission denied

# get permission
    chmod u+s ping
    sudo chmod u+s ping

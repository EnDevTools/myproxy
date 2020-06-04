# myproxy scanner


my proxy-scanner [![Python 2.6|2.7|3.x](https://img.shields.io/badge/python-2.6|2.7|3.x-yellow.svg)](https://www.python.org/) [![License](https://img.shields.io/badge/license-Public_domain-red.svg)](https://github.com/EnDevTools/myproxy)
====

Simple Python script for proxy scan to get (usable) proxies. It scan (periodically updated) list of public proxies and automatically finds in a quick manner those usable in that same moment (Note: testing of SOCKS proxies is currently possible only on non-Windows platforms).


![fetch](https://github.com/EnDevTools/myproxy/blob/master/myproxy.png)


## Git


    $ git clone https://github.com/EnDevTools/myproxy.git
   

## Building

    $ sudo apt update
    $ sudo apt install libssl-dev
    $ sudo yum install openssl-devel
    $ sudo apt install python-pip
    $ sudo apt install python3-pip
    $ pip install -r requirements.txt
    $ pip3 install -r requirements.txt
    
    
   
   
## Primary use


    $ ./myproxy
    $ ./myproxy --output=proxy.txt
    $ ./myproxy --c=france
    

Requirements
----

**MYPROXY** works out of the box with any Python version from **2.6.x** to **3.x** on any platform.


## Contact Me
https://www.facebook.com/En.Dev.Tools
Telegram @EnDevTools


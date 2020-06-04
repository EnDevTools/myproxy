# myproxy
proxy scanner by country

my proxy-scanner [![Build Status](https://github.com/EnDevTools/myproxy)](https://github.com/EnDevTools/myproxy) [![Python 2.6|2.7|3.x](https://img.shields.io/badge/python-2.6|2.7|3.x-yellow.svg)](https://www.python.org/) [![License](https://img.shields.io/badge/license-Public_domain-red.svg)](https://github.com/EnDevTools/myproxy)
====

Simple Python script for fetching "some" (usable) proxies. It fetches (periodically updated) list of public proxies and automatically finds in a quick manner those usable in that same moment (Note: testing of SOCKS proxies is currently possible only on non-Windows platforms).

Why should you use it? Well, if you've ever used free proxy lists around you'll know the pain of finding actually working proxies. This tool will automatically do the list fetching and proxy testing for you. Also, only proxies that support HTTPS traffic will be returned, which guarantees access to majority of Internet sites.

![fetch](https://github.com/EnDevTools/myproxy/blob/master/myproxy.png)

Requirements
----

**MYPROXY** works out of the box with any Python version from **2.6.x** to **3.x** on any platform.

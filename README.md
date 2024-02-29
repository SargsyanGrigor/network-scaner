# network-scaner
<div align="center">
<h1>NetVision Network Scanner</h1>
  


![image](https://github.com/SargsyanGrigor/Network-scaner/assets/106109042/f0976462-bd40-4a02-836f-699de82678cc)


# Features
<li>Scans for open ports on a specified IP address.</li>
<li>Supports scanning a range of ports or all ports.</li>
<li>Displays scan results including port number, protocol, and state.</li>
<li>User-friendly interface.</li>

# Usage

To scan a single port or a range of ports: 
    
    $ python3 NetVision.py 192.168.126.129 21
    
    $ python3 NetVision.py 192.168.126.129 21/1000

To scan all ports:

    $ python3 NetVision.py 192.168.126.129 -p-

For help:

    $ python3 NetVision.py -h
    $ python3 NetVision.py --help
    $ python3 NetVision.py help

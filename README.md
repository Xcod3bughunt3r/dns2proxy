# DNS2PROXY
#### For Offensive Cyber Security v1.0

###### Usage:
````
$ python dns2proxy.py -h
````

###### Example:
````
$ python2.6 dns2proxy.py -i eth0 -u 192.168.1.101 -d 192.168.1.200
````

###### Example for no forwarding (only configured domain based queries and spoofed hosts):
````
$ python2.6 dns2proxy.py -i eth0 -noforward
````

###### Example for no forwarding but add IPs:
````
$ python dns2proxy.py -i eth0 -I 192.168.1.101,90.1.1.1,155.54.1.1 -noforward
````

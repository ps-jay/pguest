pguest
======

PGuest is a script to authenticate with the PGuest Bluecoat appliance.

Requirements
-----

Python modules:
- requests

You might like to run it in a virtualenv:

1) virtualenv reqs
2) source reqs/bin/activate
3) pip install requests 

Config file
-----

By default, pguest will read from ~/.pguest.

The file format is:

```
username=skywalkerl
password=UseTheForks
```

Usage
-----

```
usage: pguest [-h] [-u USERNAME] [-p PASSWORD] [-c CONFIG]

Check if google is accessable, else authenticate to PGuest

optional arguments:
  -h, --help            show this help message and exit
  -u USERNAME, --username USERNAME
                        The username for authentication
  -p PASSWORD, --password PASSWORD
                        The password for authentication
  -c CONFIG, --config CONFIG
                        Path to username and password
```

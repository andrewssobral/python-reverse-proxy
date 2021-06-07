# python-reverse-proxy

A simple reverse proxy in python3

### Usage

```
./proxy.py -h
usage: proxy.py [-h] [--port PORT] [--hostname HOSTNAME]

Proxy HTTP requests

optional arguments:
  -h, --help           show this help message and exit
  --port PORT          serve HTTP requests on specified port (default: 9999)
  --hostname HOSTNAME  hostname to be processd (default: en.wikipedia.org)
```

### Example

```
(base) andrewssobral@macbookpro python-reverse-proxy % ./proxy.py   
http server is starting on en.wikipedia.org port 9999...
http server is running as reverse proxy
```

Enjoy it!

![screenshot](https://raw.githubusercontent.com/andrewssobral/python-reverse-proxy/master/images/screenshot.png)


## Proxy servers



#### What is a proxy server?

A proxy server is a server (a computer system or an application) that acts as an intermediary for requests from clients seeking resources from other servers. A client connects to the proxy server, requesting some service, such as a file, connection, web page, or other resource available from a different server and the proxy server evaluates the request as a way to simplify and control its complexity.


#### Proxy configuration

If you have the proxy server name and port, it should be rather obvious to feed that information into your browser. However, many (command line) applications depend on the variables http_proxy and ftp_proxy for correct functioning. For your convenience, you might want to add a line like the following to your ~/.bashrc.

You can edit it with *vi* text editor by typing:

```
vi ~/.bashrc
```
Then add
```
export http_proxy=http://username:password@proxy_server_name:port_number
```

For instance:
```
export http_proxy=http://willy:Appelsi3ntj3@proxy:80
```

If you do not need to give a username and password, simply leave out everything before the "@" sign, this sign included.


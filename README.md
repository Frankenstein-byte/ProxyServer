# ProxyServer
Basic Proxy Server to intercept HTTP/HTTPS traffic 

A network proxy server is an intermediary network service that users can connect to, and that relies their traffic to other servers, proxy servers can be of different types:-

* Reverse Proxies: proxies that hide the address of servers you are trying to connect to, apart from the obvious security use case, they are often used to perform load-balancing tasks, where the reverse proxy decides to which server it should forward the request, and caching. 

* Transparent proxies: these are proxies that forward your data to the server, without offering any kind of anonymity, they still change the source IP of the packets with the proxy’s IP address.

* Anonymous proxies: these are proxies that hide your identity from the target server, they are mostly used for anonymity.

By protocol, proxies also can be using a variety of protocols to accomplish their features, the most popular are:

- HTTP Proxies: The HTTP protocol supports proxy servers, the CONNECT method is used to ask the proxy server to establish a tunnel with a remote server.
- Socks Proxies: The Socks protocol, which uses Kerberos for authentication, is also widely used for proxies.


<img src=https://github.com/Frankenstein-byte/ProxyServer/blob/main/image.png width="420" height="300">


## Usage

```python
python3 socks.py
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

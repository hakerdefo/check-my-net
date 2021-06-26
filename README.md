# check-my-net

**check-my-net** is a simple bash script that can help you in checking your internet connectivity and diagnosing common internet connectivity problems.  

### Installation :

**check-my-net** doesn't have any external dependencies and it will work on any GNU/Linux system running on Linux kernel 2.2 or newer. This pretty much means everywhere. Though not tested it should work on BSDs without any problem. Installation is very simple. Download **[check-my-net-main]** zip, extract its contents and copy the file **check-my-net** to **/usr/local/bin/** directory,
```sh
sudo cp check-my-net /usr/local/bin/
```
And make it executable,
```sh
sudo chmod 755 /usr/local/bin/check-my-net
```  

### Usage :

Open terminal & run,
```sh
check-my-net
```  
And **check-my-net** will test your internet connectivity status and if internet connectivity is down it will display a diagnostic message that hopefully will be good enough to guide you towards solving the problem.  

### License :

[![Public Domain Mark](http://i.creativecommons.org/p/mark/1.0/88x31.png)](http://creativecommons.org/publicdomain/mark/1.0/)  
This work (<span property="dct:title">check-my-net</span>, by [<span property="dct:title">hakerdefo</span>](https://github.com/hakerdefo/check-my-net)), identified by [<span property="dct:title">hakerdefo</span>](https://hakerdefo.github.io), is free of known copyright restrictions.  

[check-my-net-main]:https://github.com/hakerdefo/check-my-net/archive/refs/heads/main.zip  

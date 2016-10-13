#scapy 安装
##mac
参考以下链接：

```
http://www.mamicode.com/info-detail-1249221.html
http://juhalaaksonen.com/blog/2013/12/11/installing-scapy-for-mac-os-x/
```

###安装scapy2.3.1
sudo pip install scapy


###安装graphillion
sudo pip install graphillion 


###安装dnet1.12
```
cd libdnet-1.12
./configure
make
sudo make install
cd python
sudo python setup.py install
```

###安装pcap1.1.4
```
cd pypcap-1.1.4
sudo python setup.py install
```

###安装gnuplot1.8
```
cd gnuplot-py-1.8
sudo python setup.py install
```

###安装pyx
```
cd PyX-0.10/
sudo python setup.py install
```

###安装pycrypto
```
cd pycrypto-2.6.1
sudo python setup.py install
```

###运行scapy
```
HYdeMacBook-Pro: apple$ sudo scapy
WARNING: No route found for IPv6 destination :: (no default route?)
Welcome to Scapy (2.3.2)
>>> 
```


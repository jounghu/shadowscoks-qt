# GUI 

```bash
$ sudo add-apt-repository ppa:hzwhuang/ss-qt5
$ sudo apt-get update
$ sudo apt-get install shadowsocks-qt5
```

# bash

```bash
$ apt-get install python-pip
$ pip install shadowsocks
$ sslocal -s server_ip -p server_port -l 1080 -k password -t 600 -m aes-256-cfb
```

> -k 密码要加"双引号"

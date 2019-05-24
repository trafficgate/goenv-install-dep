# goenv install-dep plugin

## Install

```shell
$ cd ~/.goenv/plugins
$ git clone https://github.com/trafficgate/goenv-install-dep.git
 :
$ goenv rehash
$ goenv global 1.12.5
$ goenv install-dep
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100  5230  100  5230    0     0   147k      0 --:--:-- --:--:-- --:--:--  154k
ARCH = amd64
OS = linux
Will install into /home/user/.goenv/versions/1.12.5/bin
Fetching https://github.com/golang/dep/releases/latest..
Release Tag = v0.5.3
Fetching https://github.com/golang/dep/releases/tag/v0.5.3..
Fetching https://github.com/golang/dep/releases/download/v0.5.3/dep-linux-amd64..
Setting executable permissions.
Moving executable to /home/user/.goenv/versions/1.12.5/bin/dep
```

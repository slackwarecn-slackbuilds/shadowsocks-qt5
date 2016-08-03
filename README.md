# slackbuild for shadowsocks-qt5

Shadowsocks-Qt5 is a native and cross-platform shadowsocks GUI client with advanced features.

## dependencies

* [qt5](https://slackbuilds.org/repository/14.2/libraries/qt5/)
* [Botan](https://slackbuilds.org/repository/14.2/libraries/Botan/)
* [qrencode](https://slackbuilds.org/repository/14.2/graphics/qrencode/)
* [zbar](https://slackbuilds.org/repository/14.2/graphics/zbar/)
* libappindicator ()

## usage

```
wget https://github.com/shadowsocks/shadowsocks-qt5/archive/v2.7.0.tar.gz
git clone https://github.com/slackwarecn/shadowsocks-qt5-slackbuild
cd shadowsocks-qt5-slackbuild
ln -s ../v2.7.0.tar.gz .
sudo sh shadowsocks-qt5.SlackBuild
```

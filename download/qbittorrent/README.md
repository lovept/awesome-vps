```bash
apt update

apt install -y wget curl 

curl -L https://github.com/userdocs/qbittorrent-nox-static/releases/download/release-4.6.3_v2.0.9/x86_64-qbittorrent-nox -o /usr/local/bin/qbittorrent-nox && chmod a+rx /usr/local/bin/qbittorrent-nox 

# 注意 第一次执行不要加 `-d`,等修改了web端的密码之后就可以加了
qbittorrent-nox -d
```
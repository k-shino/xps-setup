# xps-setup

* install Ubuntu 16.04 on Dell XPS13

## Bios configuration

## Install Ubuntu 16.04 from CD-ROM

## After installation

```bash
sudo killall -KILL apt.systemd.daily
sudo mv /etc/apt/apt.conf.d/50appstream /etc/apt/apt.conf.d/50appstream.disable
sudo apt update -y
sudo apt upgrade -y
sudo mv /etc/apt/apt.conf.d/50appstream.disable /etc/apt/apt.conf.d/50appstream
sudo apt update -y
sudo apt upgrade -y
sudo apt-get update -y
sudo apt-get upgrade -y
sudo apt install -y ssh
```


## Reference

* [Ubuntu 16.04のapt updateでappstreamcliがクラッシュする](http://grainrigi.hatenablog.com/entry/2017/08/26/232405)

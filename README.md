# xubuntu
My local files, just for backup

From 30.06.2018
<p align="center">
	<a name="top" href="https://github.com/"><img src="https://i.imgur.com/wcajJGJ.png">
	</a>
</p>

How to install Polybar on Ubuntu 18.04

wget -q -O - http://archive.getdeb.net/getdeb-archive.key | sudo apt-key add -

sudo sh -c 'echo "deb http://archive.getdeb.net/ubuntu yakkety-getdeb apps" >> /etc/apt/sources.list.d/getdeb.list'

sudo apt update

sudo apt install polybar

sudo mkdir -p ~/.config/polybar

sudo cp /usr/share/doc/polybar/config ~/.config/polybar/

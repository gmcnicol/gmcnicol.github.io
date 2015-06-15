---
title:Install Jekyll on Ubuntu 14.04 LTS

layout:post

---
The first server we're going to be running Different Circle on is a small VM hosted on [Memset](http://memset.com). I selected to use Ubuntu 14.04 LTS.

To experiment with the installation process, I've used [VirtualBox](https://www.virtualbox.org/) to run a base Ubuntu Server install locally and get it to a point of where I need it to be.

First up was getting [Jekyll](http://jekyllrb.com/) installed.

**Pre-requisites**

First up, installing Ruby. The latest version in apt-get is 1.9.3, that'll do.

    sudo apt-get update
	sudo apt-get install ruby-1.9.3

This installs everything required.

Next you need to install *build-essential*

	sudo apt-get install build-essential

**Installing Jekyll**

	sudo gem install jekyll


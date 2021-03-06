<p align="center">
  <img src="https://img.shields.io/badge/uses-ssh-blue.svg?style=flat-square"/>
  <img src="https://img.shields.io/badge/license-gpl--3-brightgreen.svg?style=flat-square"/>
  <img src="https://img.shields.io/badge/status-stable-ff69b4.svg?style=flat-square"/>
  <img src="https://img.shields.io/badge/implementation-bash / python-red.svg?style=flat-square"/>
</p>

ssh-ping
========
Check if host is reachable using ssh_config

* Outputs **Reply from** when server is reachable but login failed
* Outputs **Pong from** when server is reachable and login was successful

![](https://raw.githubusercontent.com/vaporup/ssh-tools/master/demos/ssh-ping.gif)

ssh-version
===========
Shows version of the SSH server you are connecting to

![](https://raw.githubusercontent.com/vaporup/ssh-tools/master/demos/ssh-version.gif)

ssh-diff
=========
Diff a file over SSH

![](https://raw.githubusercontent.com/vaporup/ssh-tools/master/demos/ssh-diff.gif)

ssh-facts
=========
Get some facts about the remote system

![](https://raw.githubusercontent.com/vaporup/ssh-tools/master/demos/ssh-facts.gif)

### Building and Installing the Debian Package
  ~~~~
  # apt-get install build-essential debhelper help2man

  $ dpkg-buildpackage -us -uc

  # dpkg -i ../ssh-tools_<version>_all.deb
  ~~~~

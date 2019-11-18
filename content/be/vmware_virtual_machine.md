+++
title= "VMWare"
date= "2019-09-19T16:58:58-05:00"
Description= "article de base"
Tags= ["article"]
Categories= ["article"]
+++

##### Horizon
Is a remote client display but it is extremely locked from a client side perspective.  As such any unplanified issue may leave you without solution.   
Keyboard issue/ Display issue  
plop first post

##### WMWare workstation pro 15.5
###### Installation requiring vc redist 2017
On windows, the tool requires visual c++ redistribuable 2017.
It does not precise if it is x64 branch.
Problem : this package is not provided by windows 10 installation.
In case one cannot use windows update and is a power-user there are 2 solutions:
* Install this snapshot of all vc redist version [link to come] 
* Upgrade vc2017 package using choco.
```
choco upgrade vcredist140 --version=14.12.25810
```

Installation on linux is much more convenient.

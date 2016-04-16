class: split-30 nopadding
background-image: url( https://cloud.githubusercontent.com/assets/4231611/14450892/a1c64c02-00ac-11e6-9c46-f03ab2a336cd.jpg )

.column_t2.center[.vmiddle[
.fgtransparent[
.figplaint[
![](images/openstack.png)
]
]
]]
.column_t2[.vmiddle.nopadding[
.shadelightdark[.boxtitle1[
### LTKA Labs
# OpenStack Basics

### [Eueung Mulyana](https://github.com/eueung)
### http://eueung.github.io/ET3010/openstack
#### ET-3010 | [Attribution-ShareAlike CC BY-SA](https://creativecommons.org/licenses/by-sa/4.0/)
#### 
]]
]]

---
class: column_t1 middle

.fonth4[
.tab1.fullwidth[
| Outline  |
|:-------------:|
| OpenStack - Short Introduction |
| Try OpenStack - TryStack |
| DevStack |
]]


---
class: split-30 nopadding
background-image: url( https://cloud.githubusercontent.com/assets/4231611/14450892/a1c64c02-00ac-11e6-9c46-f03ab2a336cd.jpg )

.column_t2.center[.vmiddle[
.fgtransparent[
.figplaint[
![](images/openstack.png)
]
]
]]
.column_t2[.vmiddle.nopadding[
.shadelightdark[.boxtitle1[
### 
# OpenStack - Short Intro

### 
### 
#### 
#### 
]]
]]

---
class: split-70 nopadding 
background-image: url(images/p35.jpg)

.column_t2[.vmiddle[
]]
.column_bt[.vmiddle.pushfront[
# OpenStack

OpenStack is a .yellow[cloud operating system] that .uline[controls] large pools of .bluelight[**compute**], .bluelight[**storage**], and .bluelight[**networking**] resources throughout a datacenter, all managed through the .uline[OpenStack API] or via a **dashboard** that gives administrators control while empowering their users to provision resources through a web interface.

OpenStack is mainly deployed as an .blue[**IaaS**] (Infrastructure as a Service). But it also evolves ... e.g. to this [direction](https://www.openstack.org/summit/openstack-summit-hong-kong-2013/session-videos/presentation/openstack-iaas-and-the-future-of-application-aware-infrastructure)

]]

---
class: split-70 nopadding 
background-image: url(images/p36.jpg)

.column_t2[.vmiddle[
]]
.column_bt[.vmiddle.pushfront[
# OpenStack
#### Projects &amp; Components

OpenStack clouds are powered by various OpenStack projects e.g.:
- **Nova** - Provisions and manages Virtual Machines. It can work with hypervisors
such as VMWare, Hyper-V, KVM etc.
- **Neutron** - The virtual network manager.
- **Horizon** - The user facing GUI dashboard. Implemented using Django.
- **Cinder** - Responsible for managing block storage.
- **Glance** - The VM image registry.
- ...

]]

---
class: split-70 nopadding 
background-image: url(images/p38.jpg)

.column_t2[.vmiddle[
]]
.column_bt[.vmiddle.pushfront[
# OpenStack

The OpenStack project is a global collaboration of developers and cloud computing technologists producing the .uline[open standard] cloud computing platform for both public and private clouds. 

Backed by a vibrant community of developers and some of the biggest names in the industry.

### History
- 2010 - NASA and RackSpace launches OpenStack
- 2011 - Canonical joins in
- 2012 - Red Hat joins in
- 2013 - NASA opts out, Oracle jumps in
- 2014 - HP signs in

]]


---
class: split-30 nopadding
background-image: url( https://cloud.githubusercontent.com/assets/4231611/14450892/a1c64c02-00ac-11e6-9c46-f03ab2a336cd.jpg )

.column_t2.center[.vmiddle[
.fgtransparent[
.figplaint[
![](images/openstack.png)
]
]
]]
.column_t2[.vmiddle.nopadding[
.shadelightdark[.boxtitle1[
### 
# Try OpenStack - TryStack

### [TryStack.org](http://trystack.org/)
### 
#### 
#### 
]]
]]

---
class: inverse middle center

# .blue[**\#1**] 
<hr/>
# Register &amp; Login

---
background-image: url(images/p01.jpg)

---
background-image: url(images/p02.jpg)

---
class: inverse middle center

# .blue[**\#2**] 
<hr/>
# Create Network

---
background-image: url(images/p03.jpg)

---
background-image: url(images/p04.jpg)

---
background-image: url(images/p05.jpg)

---
background-image: url(images/p06.jpg)

---
class: inverse middle center

# .blue[**\#3**] 
<hr/>
# Create Router

---
background-image: url(images/p07.jpg)

---
background-image: url(images/p08.jpg)

---
background-image: url(images/p09.jpg)

---
background-image: url(images/p10.jpg)

---
background-image: url(images/p11.jpg)

---
class: inverse middle center

# .blue[**\#4**] 
<hr/>
# Create Instance (VM)

---
background-image: url(images/p12.jpg)

---
background-image: url(images/p13.jpg)

---
background-image: url(images/p14.jpg)

---
class: split-50 nopadding 
background-image: url(images/p33.jpg)

.column_bt[.vmiddle.pushfront.right[

#PuTTYgen
####[PuTTY @ sgtatham](http://www.chiark.greenend.org.uk/~sgtatham/putty/download.html)

]]
.column_t2[.vmiddle[
]]

---
background-image: url(images/p15.jpg)

---
background-image: url(images/p16.jpg)

---
background-image: url(images/p17.jpg)

---
background-image: url(images/p18.jpg)

---
class: inverse middle center

# .blue[**\#5**] 
<hr/>
# Set Floating IP

---
background-image: url(images/p20.jpg)

---
background-image: url(images/p21.jpg)

---
background-image: url(images/p22.jpg)

---
background-image: url(images/p23.jpg)

---
class: inverse middle center

# .blue[**\#6**] 
<hr/>
# Set Access &amp; Security Rules

---
background-image: url(images/p24.jpg)

---
background-image: url(images/p25.jpg)

---
background-image: url(images/p26.jpg)

---
background-image: url(images/p27.jpg)

---
background-image: url(images/p28.jpg)

---
background-image: url(images/p29.jpg)

---
background-image: url(images/p19.jpg)

---
class: inverse middle center

# .red[Test **\#1**] 
<hr/>
# Ping Instance (VM)

---
class: split-50 nopadding 

.column_t1[.vmiddle.pushfront.right[
# Ping Test
]]
.column_t2[.vmiddle[

```bash
*$ ping 128.136.179.95

Pinging 128.136.179.95 with 32 bytes of data:
Reply from 128.136.179.95: bytes=32 time=1623ms TTL=49
Reply from 128.136.179.95: bytes=32 time=267ms TTL=47
Reply from 128.136.179.95: bytes=32 time=299ms TTL=47
Reply from 128.136.179.95: bytes=32 time=268ms TTL=47
```

]]


---
class: inverse middle center

# .red[Test **\#2**] 
<hr/>
# SSH Instance &amp; Local noVNC Console

---
background-image: url(images/p34.jpg)

---
class: split-50 nopadding 

.column_t1[.vmiddle.pushfront.right[
# SSH Test
]]
.column_t2[.vmiddle[

```bash
*login as: ubuntu
*Authenticating with public key "rsa-key-20160415"
*Passphrase for key "rsa-key-20160415":
Welcome to Ubuntu 14.04.3 LTS (GNU/Linux 3.13.0-62-generic x86_64)
...

*ubuntu@node1:~$ lsb_release -a
No LSB modules are available.
Distributor ID: Ubuntu
Description:    Ubuntu 14.04.3 LTS
Release:        14.04
Codename:       trusty
*ubuntu@node1:~$ uname -a
Linux node1 3.13.0-62-generic #102-Ubuntu SMP Tue Aug 11 14:29:36 UTC 2015 x86_64 x86_64 x86_64 GNU/Linux

# own password
*ubuntu@node1:~$ sudo -s
root@node1:~#

*ubuntu@node1:~$ sudo passwd root
Enter new UNIX password:
Retype new UNIX password:
passwd: password updated successfully
*ubuntu@node1:~$ sudo passwd -u root 
# unlock may not be necessary

# root password
*ubuntu@node1:~$ su -
```

]]


---
background-image: url(images/p31.jpg)

---
background-image: url(images/p32.jpg)


---
class: inverse middle center

# .red[Test **\#3**] 
<hr/>
# Access HTTP Server

---
class: split-50 nopadding 
background-image: url(images/p30.jpg)

.column_t2[.vmiddle[
]]
.column_bt[.vmiddle.pushfront[

```bash
*ubuntu@node1:~$ python -V
Python 2.7.6

*ubuntu@node1:~$ sudo python -m SimpleHTTPServer 80
Serving HTTP on 0.0.0.0 port 80 ...
118.137.56.43 - - [14/Apr/2016 22:18:17] "GET / HTTP/1.1" 200 -
118.137.56.43 - - [14/Apr/2016 22:18:17] code 404, message File not found
118.137.56.43 - - [14/Apr/2016 22:18:17] "GET /favicon.ico HTTP/1.1" 404 -
```

]]




---
class: split-30 nopadding
background-image: url( https://cloud.githubusercontent.com/assets/4231611/14450892/a1c64c02-00ac-11e6-9c46-f03ab2a336cd.jpg )

.column_t2.center[.vmiddle[
.fgtransparent[
.figplaint[
![](images/openstack.png)
]
]
]]
.column_t2[.vmiddle.nopadding[
.shadelightdark[.boxtitle1[
### 
# Refs

### 
### 
#### 
#### 
]]
]]

---
# Refs
.fonth5[
1. [OpenStack Open Source Cloud Computing Software](http://www.openstack.org/software/)
1. [TryStack: A Free Way To Try OpenStack With Your Apps](http://trystack.org/)
1. [Starting VMs on Trystack.org](https://www.youtube.com/watch?v=z-M5Vt4-HYg)
1. [IaaS is OVER, ladies. Time for OpenStack to jump clear](http://www.theregister.co.uk/2015/05/20/iaas_shakeout_openstack_future/)
1. [OpenStack, IaaS and the Future of Application Aware Infrastructure](https://www.openstack.org/summit/openstack-summit-hong-kong-2013/session-videos/presentation/openstack-iaas-and-the-future-of-application-aware-infrastructure)

]

---
class: split-30 nopadding
background-image: url( https://cloud.githubusercontent.com/assets/4231611/14450892/a1c64c02-00ac-11e6-9c46-f03ab2a336cd.jpg )

.column_t2.center[.vmiddle[
.fgtransparent[
.figplaint[
![](images/openstack.png)
]
]
]]
.column_t2[.vmiddle.nopadding[
.shadelightdark[.boxtitle1[
### 
# END

### [Eueung Mulyana](https://github.com/eueung)
### http://eueung.github.io/ET3010/openstack
#### LTKA Labs | [Attribution-ShareAlike CC BY-SA](https://creativecommons.org/licenses/by-sa/4.0/)
#### 
]]
]]




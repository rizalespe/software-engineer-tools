How to Connect your friend localhost
===================
--------

Hey! My name is Andi Hafiidh[^myname]. I want to share with you about how to open a **Local Website ** on another Computer or Mobile. (Responsive Web Design Testing)

----------


All You needs
-------------
- **[XAMPP][1]**
	as a server where the website are installed, the url is http://localhost/ or http://127.0.0.1/ Apache, Mysql, etc are included
	
- **[Wifi Hotspot.exe][2]**
	to make your personal wifi hotspot, I just modificate from original windows command on **Command Promt**
> I will skip about **XAMPP** instalation, I think if you know about localhost you are know about **XAMPP**


Tutorial
-----------

>Makesure you already have the application, and you have a **RWD Web Design** that will be test.

####<i class="icon-cog"></i> Create Wifi Hotspot
Open the **Wifi Hotspot.exe** (Run as Administrator).
first, program will ask what do you want as command. type `create`
```
Command:create
```
after that click <kbd>Enter</kbd>

```
Command:create

SSID:<type name of your Wifi Hotspot>
Key:<type password of your Wifi Hotspot>
```
after that click <kbd>Enter</kbd>

```
Command:create

SSID:<type name of your Wifi Hotspot>
Key:<type password of your Wifi Hotspot>

The hosted network mode has been set to allow.
The SSID of the hosted network has been successfully changed.
The user key passphrase of the hosted network has been successfully changed.

Press any key to continue . . .
```
Your Wifi Hotspot has been **Created**
after that click <kbd>Enter</kbd>

#### <i class="icon-off"></i> Start the Wifi Hotspot

```
Command:start
```
after that click <kbd>Enter</kbd>

```
Command:start

The hosted network started.

Press any key to continue . . .
```
your Wifi Hotspot now **Actived**
after that click <kbd>Enter</kbd>

#### <i class="icon-link"></i> Connect the Wifi Hotspot
As usual the other PC or Mobile connect to your Wifi Hotspot. use **SSID** and **Key** you have been declared

#### <i class="icon-list-bullet"></i> Check the IP Server
```
Command:ip
```
after that click <kbd>Enter</kbd>
```
Command:ip


Windows IP Configuration
...

Wireless LAN adapter Local Area Connection* 4:

   Connection-specific DNS Suffix  . :
   Link-local IPv6 Address . . . . . : --------------
   IPv4 Address. . . . . . . . . . . : <this your ip>
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . :

...

Press any key to continue . . .
```
after that click <kbd>Enter</kbd>

####<i class="icon-globe"></i> Open the IP Server
```
http://<this server ip>/
```

---------------------------------

List Command
---------
Some Command available in Wifi Hotspot.exe

| Command                       | Description              |
 ----------------- | ---------------------------- | ------------------
| CREATE            | make the Wifi Hotspot|
| HELP            | showing all the command are available |
| IP |showing the IP of your Computer |
| QUIT | close the aplication |
| SHOW |showing the status of the Wifi Hotspot |
| START | starting the Wifi Hotspot |
| STOP | stoping the Wifi Hotspot |



### Table of contents

[TOC]



  [^myname]: [Andi Hafiidh 145150407111065](http://kumpulinide.id/) hanya seorang mahasiswa Sistem Informasi yang pingin belajar aja dan suka mainan. 
  


  [1]: https://www.apachefriends.org/download.html
  [2]: https://drive.google.com/open?id=0B5u0SDf73JildlFfS1Q3NURHVXM
  

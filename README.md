# linux-command

## To open terminal
```Ctrl + Alt + T```

## Install Software and tools

#### $ snap find "android studio"
```Name                       Version               Publisher           Notes    Summary
android-studio             2021.1.1.21           snapcrafters        classic  The IDE for Android
android-studio-canary      2021.1.1.3            snapcrafters        classic  The IDE for Android (Canary build)
qr-code-generator-desktop  v1.0.27+git2.c64e4cb  studiolacosanostra  -        Create custom QR Codes. You can save them as PNG image. You can change the size of the image.
```

#### $ snap install android-studio --classic
```
Download snap "android-studio" (119) from channel "stable"  
44% 859kB/s 11.1m
```

## Switch to another pre-insstalled Java version

#### $ sudo update-alternatives --config java
```
[sudo] password for swarnava: 
There are 3 choices for the alternative java (providing /usr/bin/java).

  Selection    Path                                            Priority   Status
------------------------------------------------------------
  0            /usr/lib/jvm/java-11-openjdk-amd64/bin/java      1111      auto mode
  1            /usr/lib/jvm/java-11-openjdk-amd64/bin/java      1111      manual mode
  2            /usr/lib/jvm/java-17-oracle/bin/java             1091      manual mode
* 3            /usr/lib/jvm/java-8-openjdk-amd64/jre/bin/java   1081      manual mode
Press <enter> to keep the current choice[*], or type selection number:
```

## To check path
swarnava@swarnava-pc:~/Android/Sdk$ which java
/usr/bin/java
swarnava@swarnava-pc:~/Android/Sdk$ which appium
/home/swarnava/.nvm/versions/node/v16.14.2/bin/appium
swarnava@swarnava-pc:~/Android/Sdk$ which node
/home/swarnava/.nvm/versions/node/v16.14.2/bin/node
swarnava@swarnava-pc:~/Android/Sdk$ 


## To kill a process
#### $ ps aux | grep -i appium
#### $ kill -9 4542


## To change mode of file
## sudo chmod +777 Appium-Server-GUI-linux-1.22.3.AppImage



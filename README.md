# linux-command

## To open terminal by keyboard shortcut
```Ctrl + Alt + T```

## Find and Install Software and tools

#### To find software
```
$ snap find "android studio"
Name                       Version               Publisher           Notes    Summary
android-studio             2021.1.1.21           snapcrafters        classic  The IDE for Android
android-studio-canary      2021.1.1.3            snapcrafters        classic  The IDE for Android (Canary build)
qr-code-generator-desktop  v1.0.27+git2.c64e4cb  studiolacosanostra  -        Create custom QR Codes. You can save them as PNG image. You can change the size of the image.
```

#### To install software
```
$ snap install android-studio --classic
Download snap "android-studio" (119) from channel "stable"  
44% 859kB/s 11.1m
```

#### To find packages
```
swarnava@swarnava-lenovo:~$ apt-cache search openjdk-8
...
openjdk-8-jdk - OpenJDK Development Kit (JDK)
openjdk-8-jdk-headless - OpenJDK Development Kit (JDK) (headless)
openjdk-8-jre - OpenJDK Java runtime, using Hotspot JIT
...
```
```
swarnava@swarnava-lenovo:~/Desktop$ apt-cache search "OpenJDK Development Kit"
openjdk-11-doc - OpenJDK Development Kit (JDK) documentation
openjdk-11-jdk - OpenJDK Development Kit (JDK)
openjdk-11-jdk-headless - OpenJDK Development Kit (JDK) (headless)
openjdk-11-source - OpenJDK Development Kit (JDK) source files
openjdk-...
...
```
##### To install package
```
swarnava@swarnava-lenovo:~$ sudo apt install openjdk-8-jdk openjdk-8-jre
[sudo] password for swarnava: 
```

# Install package using brew
## Install Brew
<img src="https://geekflare.com/wp-content/uploads/2021/05/homebrew-social-card-e1622042135386.png" align="left" height="100" width="150" >
[Brew Home Page](https://brew.sh/)
[stackoverflow instruction](https://stackoverflow.com/a/21536379/9125727)

```
swarnava@swarnava-lenovo:/$ brew doctor
Your system is ready to brew.
swarnava@swarnava-lenovo:/$ brew update
...
swarnava@swarnava-lenovo:/$ brew install node
Running `brew update --preinstall`...
==> Downloading https://ghcr.io/v2/homebrew/core/brotli/manife
....
```

```
swarnava@swarnava-lenovo:/$ brew search appium
==> Formulae
appium
swarnava@swarnava-lenovo:/$ brew install appium
Running `brew update --preinstall`...
==> Downloading https://ghcr.io/v2/homebrew/core/appium/mani
```

## Switch to another pre-insstalled Java package(different version)

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
```
swarnava@swarnava-pc:~/Android/Sdk$ which java
/usr/bin/java
swarnava@swarnava-pc:~/Android/Sdk$ which appium
/home/swarnava/.nvm/versions/node/v16.14.2/bin/appium
swarnava@swarnava-pc:~/Android/Sdk$ which node
/home/swarnava/.nvm/versions/node/v16.14.2/bin/node
swarnava@swarnava-pc:~/Android/Sdk$ 
```

## To extract
```
$ tar -xvf <filename.xz>
```

## To kill a process
#### $ ps aux | grep -i appium
#### $ kill -9 4542


## To change mode of file
## sudo chmod +777 Appium-Server-GUI-linux-1.22.3.AppImage



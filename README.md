# termux-miunlock setup
1) pkg update
2) pkg install git
3) pkg install vim
4) git clone https://github.com/Findra2006/termux-miunlock
5) chmod +x setup.sh && ./setup.sh
6) mi-fastboot devices
7) mi-fastboot getvar product
8) mi-fastboot getvar token (SNAPDRAGON)
9) mi-fastboot oem get_token (MEDIATEK)
10) chmod +x get_token.sh && ./get_token.sh --product=PRODUCT --region=REGION --token=TOKEN DATA MI_ACCOUNT_DATA
11) mi-fastboot oem-unlock UNLOCK TOKEN

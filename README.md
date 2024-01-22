# termux-miunlock setup
  pkg update
  pkg install git
  pkg install vim
  git clone 
  chmod +x setup.sh && ./setup.sh
  mi-fastboot devices
  mi-fastboot getvar product
  mi-fastboot getvar token (SNAPDRAGON)
  mi-fastboot oem get_token (MEDIATEK)
  chmod +x get_token.sh && ./get_token.sh --product=rolex --region=global --token=m7A63YB7x9Osslxznxc67gCA MI_ACCOUNT_DATA
  mi-fastboot oem-unlock UNLOCK TOKEN

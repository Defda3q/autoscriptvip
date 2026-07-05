### Update
```apt update -y && apt upgrade -y --fix-missing && apt install -y xxd bzip2 wget curl sudo build-essential bsdmainutils screen dos2unix && update-grub && apt dist-upgrade -y && sleep 2 && reboot```

### Install
```screen -S setup-session bash -c "wget -q https://raw.githubusercontent.com/Defda3q/autoscriptvip/main/install.sh && chmod +x install.sh && ./install.sh; read -p \"Press Enter to Exit...\""```

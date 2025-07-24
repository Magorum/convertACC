# convertACC
quick script for converting ACC codec files in either the dolphin or nautilis file manager


# For Nautilus / Gnome File Manager
```
wget -O "~/.local/share/nautilus/scripts/convertACC" "https://raw.githubusercontent.com/Magorum/convertACC/refs/heads/main/convertACC"
chmod +x ~/.local/share/nautilus/scripts/convertACC
```
# For Dolphin
```
wget -O "~/bin/convertACC" "https://raw.githubusercontent.com/Magorum/convertACC/refs/heads/main/convertACC"
sudo wget -O "~/usr/share/kio/servicemenus/convert.desktop" "https://raw.githubusercontent.com/Magorum/convertACC/refs/heads/main/convert.desktop"
chmod +x  "~/bin/convertACC"
```

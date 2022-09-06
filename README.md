INSTRUCTION FOR START

1) chmod +x ./Supremo-Portable-Kali-Linux.sh
2) start the file as root
3) Enjoy

#! /bin/sh
clear
dpkg --add-architecture i386 && apt-get update && apt-get install wine32 -y
mkdir "/usr/share/Supremo/"
curl -o "/usr/share/Supremo/supremo.png" "https://icon-icons.com/downloadimage.php?id=189682&root=3053/PNG/512/&file=supremo_macos_bigsur_icon_189682.png"
curl -o "/home/kali/Scrivania/Supremo.desktop" "https://download1532.mediafire.com/p5tku7h1kqzg/5upauqn0u9q3yt3/Supremo.desktop"
curl -o "/usr/share/Supremo/supremo.exe" "https://www.nanosystems.it/public/download/Supremo.exe" 
wine "/usr/share/Supremo/supremo.exe"

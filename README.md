# Comenzi-Simple-Linux
1. In primul rand. Ai nevoie de un server care sa foloseasca sistemul de operare Linux, indiferent de distributie. (Fedora, CentOS, RedHat, Ubuntu). 
Daca doresti si vrei sa inveti, poti sa-ti instalezi orice distributie Linux pe PC-ul personal sau pe o masina virtuala(VMWARE, VirtualBox), Linux-ul va fii mereu
Tutorial scris de Manole V. Eduard.

Provideri recomandati:
OVH (Sunt destul de oke cand vine vorba de infrastuctura si de fiabilitate).
BlazingFast (VPS-uri/Servere Dedicate gazduite in Netherlands).
VPS.ag (Este vechiul host.ag, unde se vand servere foarte puternice).
iWeb.com (Cele mai puternice servere dedicate, foarte fiabile cand vine vorba de reselling.)

Comenziile pentru incepatori (Tutorial).

Intri in consola/terminal/sesiune SSH.
Ce se poate folosi ca sa te conectezi la o consola? In primul rand, sa folosesti un client precum: Putty, Mobaxterm, fiecare conexiune SSH ruleaza pe portul 22.

ls - iti afiseaza toate fiserele.
cat /proc/cpuinfo - iti afiseaza configuratia pe care o are laptop-ul tau CPU,PROC,etc.
mkdir - creezi un folder. Ex: mkdir test
cd - intri in folder. Ex: cd test
rm - stergi folder-ul/sau ce doresti. Ex: rm -rf test
username
df - iti afiseaza spatiul pe care il ai.
last - afiseaza ultimul utilizator care s-a conectat.
grep - Iti afiseaza informatia care te intereseaza, exemplu: cat /proc/cpuinfo |grep cpu
pwd - iti afiseaza locatia in care esti. ex: /home/eduard/Desktop
mv - cand vrei sa muti un fiser intr-o locatie. ex: mv test /usr/bin
wget - cand vrei sa descarci un script. ex: wget blabla.com/script.sh & chmod 755 & ./script.sh
dig - cand vrei sa aflii informatii despre DNS-ul unui site. Ex: dig google.ro
ping - trimite requesturi ICMP ca sa vezi daca conexiunea functioneaza. Ex: ping 1.1.1.1
passwd - atunci cand vrei sa-ti schimbi parola la utilizator(r00t).
clear - sterge ecranul/sesiunea pe care ai avut-o.

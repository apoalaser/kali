# kali
termux-setup-storage

pkg install wget

wget -O install-nethunter-termux https://offs.ec/2MceZWr

chmod +x install-nethunter-termux

./install-nethunter-termux

nethunter
apt-key adv --keyserver hkp://keys.gnupg.net --recv-keys 7D8D0BF6
nethunter kex passwd

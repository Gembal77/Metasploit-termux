source <(curl -fsSl https://raw.githubusercontent.com/efxtv/Metasploit-in-termux/main/metasploit-6-termux.sh)

Untuk pembenaran bila ada kesalahah.
Masukan script dibawah ini satu per satu.

1. pkg update; pkg upgrade pkg install wget curl cd $HOME;wget https://raw.githubusercontent.com/efxtv/Metasploit-in-termux/main/metasploit-6-termux.sh -q;bash metasploit-6-termux.sh

2. rm -rf /data/data/com.termux/files/usr/bin/msfvenom

3. cd;cd metasploit-framework;ln -s $HOME/metasploit-framework/msfvenom /data/data/com.termux/files/usr/bin/

4. msfconsole

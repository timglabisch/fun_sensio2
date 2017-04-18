14  wget http://media.steampowered.com/client/steamcmd_linux.tar.gz
15  tar -xvzf steamcmd_linux.tar.gz
16  ./steamcmd.sh
17  chmod +x steamcmd.sh
18  ./steamcmd.sh
31  useradd -m steam
32  sudo apt-get install lib32gcc1
33  cd /home/steam
35  su - steam
43  vim /home/steam/Steam/csgoserver/csgo/cfg/server.cfg
44  su - steam
95  cd /home/steam/Steam/csgoserver/csgo/maps/




1  mkdir ~/Steam && cd ~/Steam
5  vim ~/Steam/csgo-ds/csgo/cfg/server.cfg
6  sudo vim ~/Steam/csgo-ds/csgo/cfg/server.cfg
8  vim ~/startcsgo.sh
   
update
92  ./steamcmd.sh +login anonymous +force_install_dir ./csgoserver  +app_update 740 validate

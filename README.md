# puma_servers

# Installation

  1 - Clone this repo in /home/deploy
  
    git clone git@github.com:leonardostefani/puma_servers.git
  2- Chmod
  
    chmod 755 puma_servers/base
    chmod 755 puma_servers/base_auto_load
    chmod 755 puma_servers/base/leo.com.br.config
  3 - Service
  
    sudo cp puma_servers/puma.service /usr/lib/systemd/system/puma.service
    sudo systemctl enable puma.service

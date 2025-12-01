#Linux MInt Cinnamon Theme

![overview](overview.png)

## Quick Install

1. Install Starship  

	curl -sS https://starship.rs/install.sh | sh
	echo 'eval "$(starship init bash)"' >> ~/.bashrc

2. Drop the configs

	cp starship.toml ~/.config/
	cp config.conf ~/.config/neofetch/config.conf

3. Wallpaper mounting  
   Copy included wallpaper
   
   cp wallpaper.jpg ~/Pictures/
   # Settings → Background → Add Picture → ~/Pictures/wallpaper.jpg
   
5. Reload & check

	exec bash
	neofetch

![systemsettings](systemsettings.png)

Powered with AI and was protected by MIT License

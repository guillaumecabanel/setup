## start
```
sudo apt install -y git
sudo apt install -y zsh curl vim nodejs imagemagick jq
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
sudo reboot
mkdir -p ~/.ssh && ssh-keygen -t ed25519 -o -a 100 -f ~/.ssh/id_ed25519 -C "TYPE_YOUR_EMAIL@HERE.com"
```

## Packages
```
sudo apt install gnome-tweak-tool chromium-browser postgresql sqlite3 libsqlite3-dev default-jre redis-server openssh-server libpq-dev libxslt1-dev libxml2-dev libcurl4-openssl-dev phantomjs pdfshuffler libmagickwand-dev xclip vlc xkbset gimp ttf-mscorefonts-installer ubuntu-restricted-extras rename inkscape gnome-shell-extensions chrome-gnome-shell
```

## vscode
```
sudo apt updatesudo apt install software-properties-common apt-transport-https wget
wget -q https://packages.microsoft.com/keys/microsoft.asc -O- | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main"
sudo apt install code
```

## Gnome-extensions
- AlternateTab
- Applications Menu
- Auto Move Windows
- Emoji Selector
- GSConnect
- Internet speed meter
- Ubuntu AppIndicators
- Launch new instance
- Native Window Placement
- NVIDIA GPU Stats Tool
- Places Status Indicator
- Removable Drive Menu
- Screenshot Window Sizer
- Suspend Button
- system-monitor
- Ubuntu Dock
- User Themes
- Window List
- Window List Mod
- windowNavigator
- Workspace Indicator

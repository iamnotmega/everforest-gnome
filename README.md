# Everforest GNOME
Configuration files for the Everforest-Dark-B-LB theme on GNOME 48.

## How to install
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/everforest-gnome.git
   ```
2. Copy the configuration files:
   ```bash
   cp -r ~/everforest-gnome/themes/* ~/.themes/
   cp -r ~/everforest-gnome/icons/* ~/.icons/
   cp -r ~/everforest-gnome/extensions/* ~/.local/share/gnome-shell/extensions/
   ```
3. Load the dconf settings:
   ```bash
   dconf load / < ~/everforest-gnome/dconf-settings.dconf
   ```
4. Log out and log back in to ensure everything is applied properly
5. Enjoy!

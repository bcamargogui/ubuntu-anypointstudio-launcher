# ubuntu-anypointstudio-launcher
How to add a Desktop Item/ Task Favorites Item for "Mule Anypoint Studio"  7.x

## Create file:
```bash
sudo gedit /usr/share/applications/AnypointStudio.desktop
```

Put the bellow content on the previous created file, replacing the bracets with your local path:
```
[Desktop Entry]
Version=7.10
Type=Application
Terminal=false
Exec=[installation-directory]/AnypointStudio/AnypointStudio
Name=AnypointStudio
Icon=[installation-directory]/AnypointStudio/icon.xpm
```

## Mod permissions
```bash
sudo chmod 644 /usr/share/applications/AnypointStudio.desktop
sudo chown root:root /usr/share/applications/AnypointStudio.desktop
```

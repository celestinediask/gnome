# Gnome
## core packages
- gdm
- gnome-session
- gnome-shell
- gnome-console

## WiFi toggle missing
```
sudo mv -i /etc/network/interfaces ~/interfaces.bak
```
```
sudo systemctl restart wpa_supplicant.service
```
```
sudo systemctl restart NetworkManager
```

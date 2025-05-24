# local-configs-linux

### Apps installed

* Intellij CE
* sdkman -> java 21
* Ulauncher -> set up shortcuts
* Brave browser
* Plex server
* Thunderbird
* qbittorrent
* Bitwarden as Brave extension


### To reduce scroll speed

`xinput --list` to find the ID of my trackpad
`xinput --list-props <ID>` to list all properties of my touchpad
`xinput --set-prop <ID> "libinput Scrolling Pixel Distance" 30` to change the scroll speed.

### Plex Commands to be run

```
sudo systemctl enable plexmediaserver
sudo systemctl start plexmediaserver
sudo systemctl status plexmediaserver
```

### External monitor rgb setting

```
xrandr (to find out the display name)
xrandr --output HDMI-1 --set "Broadcast RGB" "Full" (run as a startup script)
```


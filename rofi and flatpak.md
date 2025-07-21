# Rofi and Flatpak
Picture this: one day you woke up to your newly configured Hyprland setup, only to realize that your Flatpak apps are gone from Rofi. Well, this has been the case for me.

While still available on KDE Plasma menu, every Flatpak apps have evaporated from Rofi without a trace, and there's no way to get them back.

So, my solution is: create a Bash script to cater this.

## Example
```
#!/bin/bash
flatpak run com.adamcake.Bolt &
```
Save as boltrs inside /usr/bin or anything in your $PATH. Then chmod +x it.

## Launch
<img width="379" height="413" alt="image" src="https://github.com/user-attachments/assets/d39d59b3-6f18-47e2-91d6-b95d9125a2dd" />

Not so comfortable. But much easier.

# **Linux-Setup**

Personal Arch Linux (Hyprland) configuration for future cases.
Steps for setting up after a fresh install. Install these for setting up the basic files :

1. firefox
2. fish shell
3. Fonts (noto-font-cjk, JetBrains Nerd Font, nerd-fonts-symbols)
4. gedit (text editor and later Code-OSS)
5. yay (https://github.com/Jguer/yay)
6. waybar (https://github.com/Alexays/Waybar)
7. hyprlock
8. hyprlauncher
9. hyprpaper [or hyprquickpaper (https://github.com/iamsurjog/hyprquickpaper)]
10. hypridle
11. wlogout (https://github.com/ArtsyMacaw/wlogout)
12. Sway Notification Centre (https://github.com/ErikReider/SwayNotificationCenter)
13. pavucontrol
       
# **Possible places for error:**

1. General tweaks
- Do a system update first to check for updates.
- Use xdg-user-dirs-update to update the directories so that the Pictures, Music, Downloads etc folders show up.
- Change the shell from kitty to fish using (chsh -s /bin/fish)
- Install pulsewire instead of pipewire for audio.

2. hyprquickpaper
- Check if its swww or awww while setting up hyprquickpaper in commands.sh and if it doesn't work change awww/swww --> /usr/bin/awww or /usr/bin/swww
- Make a thumbs folder in /home/nishant/.cache/quickshell 

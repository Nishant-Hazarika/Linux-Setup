# **Linux-Setup**

Personal Arch Linux (Hyprland) configuration for future cases.
Steps for setting up after a fresh install. Install these for setting up the basic files :

1. firefox
2. fish shell
3. gedit (text editor and later Code-OSS)
4. yay (https://github.com/Jguer/yay)
5. waybar-git (through yay)
6. hyprlock
7. hyprlauncher
8. hyprpaper [or hyprquickpaper (https://github.com/iamsurjog/hyprquickpaper)]
9. hypridle
10. wlogout (https://github.com/ArtsyMacaw/wlogout)
11. Sway Notification Centre (https://github.com/ErikReider/SwayNotificationCenter)
12. pavucontrol
       
# **Possible places for error:**

**1. General tweaks**
- Do a system update first to check for updates.
- Use xdg-user-dirs-update to update the directories so that the Pictures, Music, Downloads etc folders show up.
- Change the shell from kitty to fish using (chsh -s /bin/fish).
- Install pulsewire instead of pipewire for audio.
- Install these fonts (noto-font-cjk, JetBrains Mono Nerd, nerd-fonts-symbols) after fresh installation.

**2. hyprquickpaper**
- Check if its swww or awww while setting up hyprquickpaper in commands.sh and if it doesn't work change awww/swww -> /usr/bin/awww or /usr/bin/swww.
- Make a thumbs folder in /home/nishant/.cache/quickshell.
- Check whether awww-daemons or swww-daemons is running or not if the wallpaper is not changing with keybinds, if it's running but not changing rerun it again otherwise run it

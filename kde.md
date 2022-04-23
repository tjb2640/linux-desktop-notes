# KDE-related

### Middle mouse paste is getting annoying

- Right-click on the clipboard in the tray, clear its history, then hit Configure Clipboard and uncheck the "Prevent empty clipboard" option (why does this even exist???)
- Run `sudo pacman -S pkg-config yay  &&  yay -S xmousepasteblock`
- In the Autostart system settings, set xmousepasteblock to run automatically by adding `/usr/bin/xmousepasteblock` as an autostart program
- Reboot and enjoy

### TeamSpeak 3 won't launch the browser to open links

Install `teamspeak3-kde-link-fix-hack` or `teamspeak3-kde-wrapper` from the AUR instead of using the base package

# lookandfeel


The package is a Slackware plasma5 theme changer when day starts & ends  
It uses "daemon" to turn the script into daemon
which runs at login and quit on logout  
Thanks to raforg : http://raf.org/daemon

Shell script : /usr/bin/lookandfeel  
Configuration file : /etc/lookandfeel.conf  
Desktop file : /etc/xdg/autostart/lookandfeel.desktop

notify-send is used to push notifcation when theme changes

NB: because of the "sleep 5m" in the while loop  
It needs ~5min. to exit the loop on logout

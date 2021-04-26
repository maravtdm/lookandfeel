# lookandfeel


The package provide a slackbuild for plasma5  
It's an automatic theme switcher when day starts & ends  
_$START & $END can be defined in /etc/lookandfeel.conf (default values are 8:00 - 20:00)_

It uses "daemon" to turn the script into daemon
which runs at login and terminates on logout  
Thanks to ZhaoLin & raforg : http://raf.org/daemon

notify-send is used to push notifcation when theme changes

**Important :**  
To avoid the package to be removed, remember to add it to the blacklist  
``echo "lookandfeel-*" | sudo tee -a /etc/slackpkg/blacklist``

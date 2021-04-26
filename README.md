# lookandfeel


The package provide a slackbuild for plasma5  
It's an automatic theme switcher when day starts & ends  
_$START & $END can be defined in /etc/lookandfeel.conf (default values are 8:00 - 20:00)_

It uses "daemon" to turn the script into daemon
which runs at login and terminates on logout  
Thanks to ZhaoLin & raforg : http://raf.org/daemon

notify-send is used to push notifcation when theme changes

**Important :**  
Remember to blacklist the package for not to be removed by _slackpkg clean-system_  
``echo "lookandfeel-*" | sudo tee -a /etc/slackpkg/blacklist``

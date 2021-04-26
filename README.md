# lookandfeel


The package provide a slackbuild for plasma5  
It's an automatic theme switcher when day starts & ends  

It uses "daemon" to turn the script into daemon
which runs at login and terminates on logout  
Thanks to ZhaoLin & raforg : http://raf.org/daemon

notify-send is used to push notifcation when theme changes

**Important :**  
Remember to blacklist the package  
echo "lookandfeel-*" | sudo tee -a /etc/slackpkg/blacklist

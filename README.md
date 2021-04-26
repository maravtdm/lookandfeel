# lookandfeel


The package provide a slackbuild for plasma5  
It's an automatic theme switcher when day starts & ends  

It uses "daemon" to turn the script into daemon
which runs at login and quit on logout  
Thanks to ZhaoLin & raforg : http://raf.org/daemon

notify-send is used to push notifcation when theme changes

NB: because of the "sleep 5m" in the while loop  
It needs ~5min. to exit the loop on logout

Important :  
Remember to blacklist the package 
echo "lookandfeel-*" | sudo tee -a /etc/slackpkg/blacklist

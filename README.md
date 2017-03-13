# project-hotspot/thnx to AdnanHodzic
automatic install for anon-hotspot
First get a wireless internet connection
Then give the installer in the directory project-hotspot "chmod +x installer"
Then " ./installer "
Follow the install instructions
When thats done go to applications=>settings=>session and startup=>Application autostart=>click add=>give it a name=>click next to command=>go to root=>project-hotspot=>click startup.sh and click ok
Type in the terminal " cd /etc/lightdm "
Then type " nano lightdm.conf "
Then remove # before autologin-user= "and typ root after = "
Then remove # before autologin-user-timeout=0
Save that
And reboot ur system
have fun

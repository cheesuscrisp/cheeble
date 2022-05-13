# cheesus's Guide to unblocking websites.

In order of convenience, the methods are:
1. Using any DPI-bypass technique
2. Using a VPN.
3. Using some proxy/unblocking method (make sure it's trusted and don't enter personal details in it. If you're making an account there, then use a different password that's dissimilar from all your other ones.



## 1. DPI-Bypass:
**IMPORTANT** - This isn't foolproof against piracy detection measures of your ISP. If you live in an area where piracy can be detected and you can face actual punishment for it, don't rely on this measure. USE A VPN IF YOU'RE NOT SURE, or just use legal services. I hold no responsibility for the decision you make and the consequences that follow. Make your own decision.
Also, this doesn't go around geo-restricted content blocks. ie. it won't let you use Indonesian Netflix from Germany. It will only unblock the websites, but whether or not the website itself shows content is outside of the scope of this method.

That being said, this method is fairly tedious to setup (around 2 mins, and some thinking), but once set up, you can just forget about website unblocking.

### Windows
[Download GoodbyeDPI](https://github.com/ValdikSS/GoodbyeDPI/releases) - Make sure the green latest indicator is there next to it, and click the "goodbyedpi-x.x.x.zip" file. [images](https://i.imgur.com/JycWqYu.png)

Extract the file and move it to a safe folder, say documents.
To extract, use the inbuilt windows one, or use [7zip](https://www.7-zip.org/)

Now open the folder.

You can do 2 things here (assuming you aren't from russia)

Either run the normal script which doesn't run as a service (not recommended, but no prep required)
or Install the script as a windows service (recommended, takes about 2 mins to do)

- **Installing the script as a windows service:**
	- Right click the "service_install_russia_blacklist_dnsredir" and click edit.
	- Go back to file explorer, but don't close the notepad window that opened.
	- Right click the "2_any_country_dnsredir" and click edit, similar to step 1.
	- Copy the "-5 --dns-addr 77.88.8.8 --dns-port 1253 --dnsv6-addr 2a02:6b8::feed:0ff --dnsv6-port 1253" from the "2_any_country_dnsredir" and paste it *replacing* the same in the "service_install_russia_blacklist_dnsredir" **till the apostrophe(") before "start" (DO NOT REMOVE BOTH THE APOSTROPHES, ONLY REMOVE 1 - refer finished result)**
  - [finished result image](https://i.imgur.com/srBkl9b.png)
	- Now save and close both notepad files.
	- right click the edit file, ie. the "service_install_russia_blacklist_dnsredir" and run as admin.
	- it should now run in the background as a service. 

- **Checking if you have installed it properly:**
	- to make sure, you can go to task manager by pressing control+shift+esc.
	- click the more details tab if you haven't already
	- click services in the top menu
	- press the "g" key
	- check if goodbyedpi is there.

### MacOS:
[SpoofDPI](https://github.com/xvzc/SpoofDPI/releases) - download the macos version by clicking the "spoof-dpi-osx.tar.gz" file under assets, making sure that the latest green indicator is there in the release. (refer the windows download process if you're new to GitHub downloads)

Just right click and open and it'll run in the terminal itself. Don't quit terminal or the script will terminate. Just minimize it to the dock. Automating it is too much of a pain in mac so I wouldn't recommend doing it if you're new. Just open the script whenever you want to bypass blocked sites.


## 2. Using a VPN:
Free VPNs are notoriously bad for privacy. Using a paid VPN is highly recommended, especially if you live in a part of the world where piracy has actual consequences.
Refer [privacytools](https://www.privacytools.io/#vpn) or [privacyguides](https://www.privacyguides.org/vpn/).


## 3. Using a proxy/unblocking website:

This method is fairly unreliable, but can be quick and convenient. No setup required.

[Websites](https://www.reddit.com/r/FREEMEDIAHECKYEAH/wiki/storage#wiki_piracy_site_proxies) - Collection of sites for unblocking sites. Credit to FMHY and u/nbatman. I don't personally use this method, but I can see how it could be useful.

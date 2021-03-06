# Windows 10 Clean Install - 1909

## Install

Do not use the default settings, turn microphone off (Cortana will be disabled later)

## Let it download all the updates
Once you get to the desktop, go to **Settings > Updates and Security > Windows Update**, and let it download all the updates. 
Reboot and repeat until no more updates are available.  
This is important because Windows Update may interfere with our activities.

![](https://raw.githubusercontent.com/jlagden/Windows10Clean/master/Updates.PNG) 

Now open the Store app, and let it download updates too.  
Again, this is important because updates would interfere with our activities.  
This may take some time. 
s
![](https://raw.githubusercontent.com/jlagden/Windows10Clean/master/StoreDownloadUpdates.png)

![](https://raw.githubusercontent.com/jlagden/Windows10Clean/master/StoreUpdates.png)  

Make sure you check for updates several times, because we absolutely don't want it to download stuff while we're removing it.

Now that the system is fully updated, make sure Windows is activated with your license.

## Remove everything you can

Remove all possible Metro Apps (except Store)

Then use the following powershell commands to remove remaining apps

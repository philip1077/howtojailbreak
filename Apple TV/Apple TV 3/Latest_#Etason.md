# Jailbreak Apple TV 3

You will need:

1. Apple TV 3 (Model A1469) connected to your TV and power.
2. Apple TV remote.


### Step 1

Make sure your Apple TV is connected to the internet, either wirelessly or ethernet.


### Step 2

Go to the `Settings` app, then under `General` select Network. Next, click the network you are currently on, and you should see network options come up. _Now is a good idea to write down, or remember your Apple TV IP address for later._ Go down to the DNS where it says `Automatic` and change it to Manual by clicking it.

### Step 3

You should see a seperate page come up asking for a DNS, replace the current DNS with: **45.166.144.59**


### Step 4

After you have entered the correct DNS and saved it, go back to the Main Menu by holding down the Menu button on the remote. Next, go back into the `Settings` app and click on the `General` once more. Scroll down until you see *`Send Data to Apple`*. You must scroll over top of the `Send Data to Apple` button, but do not click it (if you did it's no big deal, just press the menu button once to go back), instead press the *Play/Pause* button on the remote. 


### Step 5

You will then see a new menu come up asking to add a profile, click add profile and type: `http://trailers.apple.com/trailers.cer`

Click submit.


### Step 6

Return to the Main Menu by holding the menu button for a few seconds, then go to the Trailers app. Click it, and you should see a *#etason* come up, and click it. Your Apple TV will restart, and once it has, you are jailbroken. You can reset the DNS back to automatic after it is turned on.


### Step 7

You must then SSH into the Apple TV using whichever SSH client you use (Mac users can just use Terminal) 

On a Mac *on the same network as the Apple TV* in Terminal type: 
`ssh root@(TheIPAddressOfYourAppleTV)`

You will then be prompted for a password, which will be:
`alpine`

### Step 8

Now that you are into your ATV, there is one final command you must type to make sure that the Jailbreak is Untethered. You can do this by typing:
`dpkg -i /private/var/root/untether.deb`

## Step 9

From there you can install Cydia by going to the Trailers App, (which will now be the NitoTV App) and going over to the subsequent Apps header and installing Cydia. 

##### That's it, your Jailbroken!
***Special Thanks to @JTV#5846 on Discord for helping organize these tutorials!***

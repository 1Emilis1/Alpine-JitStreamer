# Alpine-JitStreamer
Enable JIT, without a computer!
(PC is required for initial setup.)

# Getting Ready
 First, download JitterBugPair To your Computer from [here](https://github.com/osy/Jitterbug/releases)
 Then, download Alpine-JitStreamer.zip to your iPhone or iPad.
 Download UTM SE and Tailscale from the App Store. Open the Tailscale app and make an account.

Also make sure that your certificate is an iPhone Developer or an Apple Developer, otherwise it will not work.

# Setup

Connect your iPhone or iPad to your computer and open the JitterBugPair app, then tap trust on your phone and start the app again, you will see a file appear.

Also, open iTunes and select your device, then scroll down and make sure the option "Sync with this iPhone over Wi-Fi" is turned on.

Now rename the files extension from ".mobiledevicepairing" to ".plist", after you did this send the file to your iPhone by mailing it to yourself, over Discord, etc. 

Open UTM SE, go to Settings and select "Continue running VM in the background" and "Disable screen dimming when idle".

Also make sure that you are on Wi-Fi and not on mobile data.

# VM Setup

Once you have downloaded the Alpine-JitStreamer.zip file, extract it. Then find copy the Alpine-JitStreamer file and search for an folder (make sure you are searching "On My iPhone") named: UTM SE, after you found that folder, paste the file.

Now, open the UTM SE app and start the VM, wait for it to start up (takes a long time sadly), then enter the username: root, after you did this run the command: ./JitStreamer.sh , and then copy the link to login with tailscale, paste the link into a browser and login. Go back to UTM SE and it should say success!

Then copy the Server IP provided by Alpine-JitStreamer.

Now install this [shortcut](https://www.icloud.com/shortcuts/7b44f6df4b324591a5498bb30b71cc6a) and follow the setup.
Your UDID is the same as the file name of the plist file.

# Finish

Now enable tailscale from the app, start the shortcut and quickly switch to the UTM SE app window. Now wait until it gives a selection of apps to enable JIT for. (It might take a long time for the window to appear)

JIT is disabled when you close the app.

# More info

If you have an iPhone X or older, you can jailbreak with palera1n and enable JIT no problem (look it up)

If you also have an iPad with an A11 chip or older you can also jailbreak with palera1n and enable JIT (once again, look it up)

If you have iOS 16.6.1 (including 17.0.0) or earlier, you can most likely install TrollStore (not a jailbreak, permanent signing with JIT, look it up)

Also make sure to look if checkra1n or palera1n supports your iOS version!!! (For A11 chips or older)

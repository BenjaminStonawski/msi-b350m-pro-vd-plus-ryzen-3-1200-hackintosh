# Handoff fix for Fenvi T919
For me Handoff didn't work right after installing macOS, so I needed to do some trickery to get it working. <br>
The fix was that macOS needs to generate a new Handoff key so your network card can communicate with your other devices and get data about what applications are open or what has been copied to the clipboard. <br>
To achieve this, you'll need to open the <i>Keychain Access</i> app, on the left hand side, select <i>'login'</i> and search for <i>'handoff-own-encryption-key'</i>, right click on it and click on delete.
![](https://media.discordapp.net/attachments/415562092138070018/1216533984000082071/Screenshot_2024-03-11_at_AM_12.50.30.png?ex=6600bc8f&is=65ee478f&hm=d4b97f74ec7b516e4c5f22041bde9655e92800dcf0fd3bf431c58d79080ed8be&=&format=webp&quality=lossless)
At this popup, hit delete again.
![](https://media.discordapp.net/attachments/415562092138070018/1216534403702853672/Screenshot_2024-03-11_at_AM_12.52.57.png?ex=6600bcf3&is=65ee47f3&hm=482a081d1ee098f81279422195024331f09eee20ba7b198d42be4d441c2c35d1&=&format=webp&quality=lossless)
<i>Note: sometimes this popup window won't appear, if you experience the same issue, just try to relaunch the app or click "iCloud" on the left hand side and click on "login" again and try to search for the handoff-own-encryption-key and try to delete it again.</i><br>
After that, you'll need to sign out from Apple ID and reboot your system. <br> <i>Note: keep a copy of everything (like Calendar, etc.) if it's asked.</i><br>
## After reboot
After reboot, you just need to sign back in to your Apple ID, and Handoff should work now, if not, try restarting the system again.

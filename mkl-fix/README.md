# MKL (Intel Math Kernel Library) fix for AMD CPUs
Lot of applications (for example Discord, Photoshop, CleanMyMac X, etc.) crash or won't function properly due to MKL. That's because macOS's applications try to use specific Intel functions in the app, which are in the so-called 'Math Kernel Library'. If macOS tries to use functions from this library, the apps will immediately crash because these are not available using an AMD CPU.
## How to fix this?
Well, we need to prevent macOS from running MKL functions within applications by creating a launch agent which disables MKL in the applications. <br> For that you will need to download the 'environment.plist' (written by [Pavo-IM](https://github.com/Pavo-IM)) file from the repo and put in the folder of the launch agents.

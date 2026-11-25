# NotifyRelay Sender for Mac

Download the numbered **DMG** from the [latest Mac release](https://github.com/mkellerman/notification-relay/releases/latest). The app supports Apple silicon and Intel Macs running macOS 14 or later. Capture requires a compatible Notification Center database and Full Disk Access.

On a new Mac, open the disk image and drag **NotifyRelay Sender** onto **Applications**. Eject the image and open the app from Applications. Choose your Apple push key and pair your iPhone by QR.

If you already run a development build, open the app on the disk image and choose **Install in Applications**. If it reports a different active sender, choose **Stop Forwarding** in the installed app, retry the installation, then choose **Start Forwarding at Login** in the updated app. Your key and pairing carry over. Future updates are available under **Advanced → Software Updates**.

## Update verification

Sparkle verifies the [update feed](https://github.com/mkellerman/notification-relay/releases/latest/download/appcast.xml) and download using a public key embedded in the installed app. The initial Ed25519 verification key is `Hx8bjYkzsWZPftlNLdqPzHFgMUZ+lu6GqK9uX+ixAl0=`.

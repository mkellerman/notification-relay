# NotifyRelay Sender for Mac

[Download the latest notarized Mac release](https://github.com/mkellerman/notification-relay/releases/latest). Choose the numbered ZIP under Assets. The app supports Apple silicon and Intel Macs running macOS 14 or later. Capture requires a compatible Notification Center database and Full Disk Access.

Unzip the app, open **NotifyRelay Sender**, and choose **Install in Applications**. On a new Mac, choose your own Apple push key and pair your iPhone by QR. Install the first updater-enabled release manually on each Mac, then use **Advanced → Software Updates** for future updates.

## Update verification

Sparkle verifies the [update feed](https://github.com/mkellerman/notification-relay/releases/latest/download/appcast.xml) and download using a public key embedded in the installed app. The initial Ed25519 verification key is `Hx8bjYkzsWZPftlNLdqPzHFgMUZ+lu6GqK9uX+ixAl0=`.

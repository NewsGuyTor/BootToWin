# BootToWin 

![bootcamp-github](https://user-images.githubusercontent.com/19603024/81490701-91a47000-9285-11ea-9ec5-bd5d4c96377d.png)

## Small macOS menu bar app for quick booting into Windows (OpenCore)

I was getting annoyed by having to open up System Preferences to reboot directly into Windows, so I made a simple macOS menu bar app that makes rebooting into Windows much simpler and faster.

The app is just a [Platypus](https://sveinbjorn.org/platypus) app with some simple bash and Applescript + shiny icons. The script itself is embedded within the .app, and can be edited by you if you want.

After installing the app by dragging it to your Applications folder, I also recommend setting it to launch from boot (so it'll always be accessible from the menu bar). You can do that from System Preferences - Users & Groups.

[System Integrity Protection (SIP) must be disabled](https://totalfinder.binaryage.com/sip#mark-how-to-install-totalfinder-by-turning-off-system-integrity-protection) for this to work unfortunately. You also need a working dual boot setup, where you can boot into Windows from System Preferences - Startup Disk.

I've only been able to test this on my own machine so far, but it should work fine for other configs. In case something doesn't work it'll probably just not work, it's so simple that I can't really see it actually break anything. If a bug is found I'll try to fix it and release an updated version. :)


Download:
https://github.com/NewsGuyTor/BootToWin/releases/latest

Source code:
https://github.com/NewsGuyTor/BootToWin

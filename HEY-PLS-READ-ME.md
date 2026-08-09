# spectral-limiter
The official GitHub repository for Prism Audio's Spectral Limiter plugin!

Hey there, thank you for downloading our spectral limiter plugin! Down here there are some important things you need to do if the plugin is giving issues.
Enjoy!

--------------------

**NOTE FOR MacOS USERS (Unsigned indie build)**

Because this is a community open-source release, the binaries are not code-signed with an Apple Developer Account! If your DAW or the computer itself blocks the plugin or says it is "damaged", you can either:
go into the Mac settings, hit the Privacy and Security tab, then scroll to the end, find the plugin and click "Authorize" or "Open anyway";
simply open your Mac's Terminal app and run the following command to clear Apple's internet quarantine flag:
xattr -cr /Library/Audio/Plug-Ins/VST3/SpectralLimiter.vst3

(replace .vst3 with .component if you are using the Audio Unit version in Logic).

> *IF ISSUES PERSIST PLEASE CONTACT US THROUGH EMAIL OR BY LETTING US KNOW INSIDE THE “PRISM-PLUGINS-ISSUES” CHANNEL IN OUR DISCORD SERVER*

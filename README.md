# FOSS Setup
A repository containing a wide list of recommended software to achieve a fully-functioning technical presence based on FOSS (free [as in freedom], open source software), with digital privacy and security as priorities. Each app or service will have the following information listed:
1. On the left of the name will be an emoji, indicating the operating system supported. a 🖥️ symbol means that the software works on Linux (primarily Fedora 40 KDE spin, as that is what I use), a 📱 symbol represents that the software works on Android phones OR GrapheneOS, an alternative privacy-focused Android fork, and the symbol 🛜 represents that it supports both Android and Linux. Software may also support other operating systems, such as Windows or iPhones, but they will not be indicated here. All Android software will work on phones that are unrooted.
2. Each listing will have the name of the software, which will be a link back to the main page of it. This will be the official website of the software, if one exists. If none exists, then the github will be linked. If there is no github page, the most relevant page I can find will be linked.
3. On the right of the name may or may not be 🐐 icon. If present, it means I personally use it and can vouch for it. If not, then I have heard good enough things for it to be included, or used to use it, but I do not anymore.
4. Under the name will first be listed if the app is Gratis (meaning free of cost), Freemium, Paid, and/or self-hostable. If there is no ability to use the service indefinitely without money, it will be considered paid. If you can, but with some features locked behind paying, it will be considered freemium. If there is no payment except for minor features (such as a donation badge) then it will be considered free. Self-Hostable will be an additional tag applied to any software which can be self-hosted. For example, Zotero has most features free, some behind a paywall, and the ability to self-host to gain all features for free. It would be marked as Freemium, Self-Hostable.
5. Next to the payment model of the software will be a quick listing of methods of download. These can include (non-exhaustive): F-Droid repository, Izzyondroid repository, Google Play Store, side-loaded APK file, AppImages, Snap, Flatpak, RPM repository, Fedora 40 KDE repository, custom repository, etc. Only one-two will be listed per app, with AppImages, Snap, and side-loaded APKs being de-prioritized over the others.
6. Next, each entry will either be marked "FOSS Frontend" or "Fully FOSS." Freetube, for example, is a FOSS frontend of Youtube. Youtube itself is in no way FOSS, but Freetube provides a way to access it using a FOSS frontend, and thus is marked as a FOSS Frontend. Peertube, on the other hand, is a FOSS Youtube alternative, and as such will be labelled Fully FOSS.
7. Next, each entry will be marked as "Active" "Intermittent Development" or "Inactive", depending on how actively updates are pushed. Different software will have different levels of leniency here, as some software simply needs updates more often than others.
8. Finally, software with android support will be marked as "Shizuku-Enhanced", "Shizuku-Required", or "Default-Permissions". Apps that provide extra features if you use Shizuku will be marked as Shizuku-Enhanced, apps that only provide functionality with Shizuku will be marked as "Shizuku-Required", and apps with no special features for those who use Shizuku will be marked as "Default-Permissions." 
9. A little information will be given under each listing about it, as well as tips

Note: Software may be listed under multiple sections, should they be relevant to more than one.

# Sections:
[Software Stores, Managers, and Finders](#software-stores-managers-and-finders)  
[Terminal Emulators](#terminal-emulators)  
[File Managers](#file-managers)  
[Android Launchers](#android-launchers)  
[Android Keyboards](#android-keyboards)  
[VPNs](#vpns)  
[DNS](#dns)  
[Clearnet Browsers](#clearnet-browsers)  
[Firefox Addons](#firefox-addons)  
[Search Engines](#search-engines)  
[Darknet Access](#darknet-access)  

# Software Stores, Managers, and Finders
These are software capable of discovering other software and/or download other software. These recommendations can be used in tandem with one another to obtain most other apps on this list. 

- ### 🖥️ [Discover](https://apps.kde.org/discover/) 🐐
   *Gratis, Fedora 40 KDE Repository, Fully FOSS, Active*  
   The Discover store is the main store when using the KDE desktop environment. It allows you to install software from a wide variety of repositories, as well as search for software by category, and read reviews. Overall an effective software store.
- ### 🖥️ [Software](https://apps.gnome.org/Software/)
   *Gratis, Fedora 40 Gnome Repository, Fully FOSS, Active*  
   The main software store for the Gnome desktop environment. It allows you to install software from a wide variety of repositories, as well as search for software by category, and read reviews. Overall an effective software store.
- ### 📱 [Aurora Store](https://auroraoss.com/)
   *Gratis, F-Droid repository, Fully FOSS, Active, Default Permissions*  
   Allows you to download and update apps from the Google Play Store anonymously. There are rumors that signing in may get your Google account banned so... don't do that maybe.
- ### 📱 [F-Droid](https://f-droid.org/en/)
   *Gratis, Side-loaded APK OR F-Droid repository, Fully FOSS, Active, Default Permissions*  
   F-Droid allows you to, shockingly, download apps from the F-Droid repository, as well as other repositories if you add them. A great solution to download FOSS apps on your phone.
- ### 📱 [IzzyOnDroid](https://gitlab.com/sunilpaulmathew/izzyondroid)
   *Gratis, Side-loaded APK OR IzzyOnDroid repository, Fully FOSS, Active, Shizuku-Enhanced*  
   An unofficial app to download apps from the IzzyOnDroid repository, one of the most popular repositories for FOSS apps on android.
- ### 📱 [Droidify](https://github.com/Droid-ify/client) 🐐
   *Gratis, Side-loaded APK OR F-Droid repository, Fully FOSS, Active, Shizuku-Enhanced*  
   Droidify is an alternative app for downloading apps on your phone, with a high number of repositories included (most notably F-Droid and IzzyOnDroid) as well as Material You theming. Very pretty, very functional.
 - ### 📱 [Obtainium](https://github.com/ImranR98/Obtainium) 🐐
   *Gratis, F-Droid repository, Fully FOSS, Active, Shizuku-Enhanced*  
   An app that allows you to compile and obtain apps directly from Github, removing the middle-man of an app like F-Droid or Droidify. Also very useful for apps that simply are not in any repository. 
 - ### 📱 [Apps](https://github.com/GrapheneOS/Apps) 🐐
   *Gratis, GrapheneOS Default App, Fully FOSS, Active, Default Permissions*  
   The built in App Manager for GrapheneOS phones, allowing you to manage, update, and install official GrapheneOS apps. Not very exciting admittedly.
- ### 📱 [App Manager](https://github.com/MuntashirAkon/AppManager) 🐐
   *Gratis, F-Droid repository, Fully FOSS, Active, Shizuku-Enhanced*  
   A powerful app capable of intsalling APK files, sharing APK files, viewing in-app trackers, seeing app usage, signing apps with custom signatures, and so much more.

# Terminal Emulators
Software that provides you with access to a terminal, to run commands.

- ### 🖥️ [Konsole](https://apps.kde.org/discover/) 🐐
   *Gratis, Fedora 40 KDE Repository, Fully FOSS, Active*  
   The built-in terminal emulator on the KDE Desktop Environment. Highly customizable, but also simple to use. 
- ### 🖥️ [Console](https://apps.gnome.org/Console/)
   *Gratis, Fedora 40 Gnome Repository, Fully FOSS, Active*  
   The built-in terminal emulator on the Gnome Desktop Environment. Easy to use, and powerful.
- ### 📱 [Termux](https://termux.dev/en/) 🐐
   *Gratis, F-Droid Repository, Fully FOSS, Active, Shizuku-Enhanced*  
   A fully-working Linux terminal emulator for use on Android phones. Works with Shizuku or even automation apps to provide even more functionality... people install entire DEs on their phone with this.

# File Managers
Software that allows you to manage your files when using a GUI

- ### 🖥️ [Dolphin](https://apps.kde.org/dolphin/) 🐐
   *Gratis, Fedora 40 KDE Repository, Fully FOSS, Active*  
   The built-in file manager on the KDE Desktop Environment. Highly customizable, but also simple to use. 
- ### 🖥️ [Files](https://apps.gnome.org/Nautilus/) 
   *Gratis, Fedora 40 Gnome Repository, Fully FOSS, Active*  
   The built-in file manager on the Gnome Desktop Environment. Easy to use, and powerful. Also known as Nautilus.
- ### 📱 Files 🐐
   *Gratis, GrapheneOS Default App, Fully FOSS, Active, Default-Permissions*  
   A genuinely fantastic files manager that is built into GrapheneOS. Connects with online accounts such as Nextcloud and Google Drive, and even provides access to the usually restricted Android/data folder. I could not find a link for this one.
- ### 📱 [Material Files](https://github.com/zhanghai/MaterialFiles)
   *Gratis, F-Droid Repository, Fully FOSS, Active, Default-Permissions*  
   A beautiful file manager app that uses Material You design. While not the most powerful file manager on the market, it is likely the prettiest, and it works for all basic functions that most people use.
  
# Android Launchers
The launcher of a phone basically controls what your home screen looks like. It's important to find one that works well for your workflow.

- ### 📱 [Neo Launcher](https://github.com/NeoApplications/Neo-Launcher)
   *Gratis, F-Droid repository, Fully FOSS, Active, Default Permissions*  
   A launcher that replicates much of the GUI of the default pixel launcher. If you want a traditional experience but FOSS, this is likely your go-to.
- ### 📱 [Kiss Launcher](https://kisslauncher.com/)
   *Gratis, F-Droid repository, Fully FOSS, Active, Default Permissions*  
   Another search-based launcher. Extremely powerful search bar allowing you to find apps and more on your phone easily. In my humble opinion, much worse widget support than Kvaesitso.
- ### 📱 [Kvaesitso](https://kvaesitso.mm20.de/) 🐐
   *Gratis, F-Droid repository, Fully FOSS, Active, Default Permissions*  
   A search-based launcher. Clean homescreen to show off your wallpaper, with a search bar allowing you to search for apps, shortcuts, files, contacts, and so much more. Single page, where you can scroll down to see widgets.

# Android Keyboards
To, you know, allow you to type. You don't want to be keylogged.

- ### 📱 [Heliboard](https://github.com/Helium314/HeliBoard) 🐐
   *Gratis, F-Droid repository, Fully FOSS, Active, Default Permissions*  
   A great keyboard that is deeply customizable and provides most that one would need. Even provides swipe typing, although sadly you need to download a library from google for it.
- ### 📱 [Florisboard](https://github.com/florisboard/florisboard)
   *Gratis, F-Droid repository, Fully FOSS, Intermittent Development, Default Permissions*  
   A very customizable keyboard, even moreso than Heliboard. However, lacks swipe typing for those who use it.

# VPNs
VPNs, or Virtual Private Networks, are services that provide a proxy between your device and your internet traffic. The privacy implications of this are often overstated, but it can help to a certain degree, and it can also prevent geoblocking of content.

- ### 🛜 [Mullvad](https://mullvad.net/en)
   *Paid, Flatpak OR F-Droid repository, Fully FOSS, Active, Default Permissions*  
   Likely the best VPN out there for privacy reasons, as they have a proven track record (not just promised track record) of keeping no logs.
- ### 🛜 [Proton VPN](https://protonvpn.com/)
   *Paid, Flatpak OR F-Droid repository, Fully FOSS, Active, Default Permissions*  
   Another really great VPN, that has long-promised and been audited to be keeping no logs. Unlike Mullvad, supports port forwarding, which is useful when torrenting for example.

# DNS
DNS, or Domain Name System, can be likened to a phonebook - it basically tells your phone or computer where to locate websites and other resources on the internet. By running your own DNS server, you can block access to resources you don't like - such as ads - by preventing devices on your network from locating the resources needed to load them.

- ### 🛜 [NextDNS](https://nextdns.io/) 🐐
   *Freemium & Self-Hostable, CLI only, Fully FOSS, Intermittent Development, Default Permissions*  
   A highly customizable DNS, allowing you to block specific ads trackers, and websites highly effectively device-wide.

# Clearnet Browsers
GUI Apps that allow you to access webpages on the clearnet (the "normal" internet). 

- ### 🛜 [Firefox](https://www.mozilla.org/en-US/firefox/) 🐐
   *Gratis, Fedora 40 KDE Repository OR Google Play Store, Fully FOSS, Active, Default Permissions*  
   A long-standing browser built with privacy in mind. DOES come with some telemtry and stuff, but for most people that is no issue, and it is all removable should you choose to. Also fast and highly customizable, supporting many addons and themes.
  - ### 🖥️ [Arkenfox](https://github.com/arkenfox/user.js) 🐐
    *Gratis, Manual Installation from Github, Fully FOSS, Active*  
    A custom config you can enable in the default Firefox app (so you still get Mozilla's quick security updates) that hardens the browser to make it extremely privacy-focused. Still has all the functionality of default Firefox, but with much superior privacy.
  - ### 🖥️ [Betterfox](https://github.com/yokoffing/Betterfox)
    *Gratis, Manual Installation from Github, Fully FOSS, Active*  
    A custom config you can enable in the default Firefox app (so you still get Mozilla's quick security updates) that provides greater privacy, speed, and efficiency. Breaks less sites when compared to Arkenfox, but is far less private.
- ### 🖥️ [Mullvad](https://mullvad.net/en/browser)
   *Gratis, Flatpak, Fully FOSS, Active*  
   A fork of Firefox built to bring fingerprinting to an absolute minimal while still using the clearnet (unlike Tor). Makes you practically invisible if you don't sign in, but you should not customize it in any way whatsoever or you will break your privacy.
- ### 🖥️ [Librewolf](https://librewolf.net/)
   *Gratis, Flatpak, Fully FOSS, Active*  
   A fork of Firefox that is hardened by default - sort of like Arkenfox, but with every so slightly slower security updates, ever so slightly less extension support, but it is all set up for you.
- ### 🖥️ [Floorp](https://floorp.app/en/)
   *Gratis, Flatpak, Fully FOSS, Active*  
   A fork of Firefox providing some features that many consider to be missing from base Firefox - for example, vertical tabs, a sidebar, an easier profile changer, and so on.
- ### 🛜 [Brave](https://brave.com/)
   *Gratis, AppImage OR Google Play Store, Fully FOSS, Active*  
   A Chromium based browser that attempts to provide better privacy than other Chromium browsers. Has built-in ad and tracker blockers.
- ### 📱 [Mull](https://gitlab.com/divested-mobile/mull-fenix) 🐐
   *Gratis, F-Droid Repository, Fully FOSS, Active, Default Permissions*  
   A fork of Firefox that is hardened by default, similar to Librewolf but on Android. Makes many security and privacy changes based on Arkenfox and the Tor Project.
- ### 📱 [Iceraven](https://github.com/fork-maintainers/iceraven-browser) 🐐
   *Gratis, Side-Loaded APK, Fully FOSS, Active, Default Permissions*  
   A fork of Firefox providing some features many consider to be missing from Firefox on Android- for example, about:config support, tab suspension, more add-on support, and so on.
- ### 📱 [Vanadium](https://github.com/GrapheneOS/Vanadium) 🐐
   *Gratis, GrapheneOS Default App, Fully FOSS, Active, Default Permissions*  
   A Chromium based browser that has been hardened, and works as the default browser on GrapheneOS. Also provides the WebView.

# Firefox Addons
Extensions to the functionality of Firefox, or any of its various forks, by third parties. Some of these may have chromium equivalents, however this will focus purely on Firefox extensions.

- ### 🖥️ [Languagetool](https://languagetool.org/) 🐐
   *Gratis, Firefox Addons, Fully FOSS, Active*  
   A grammar and spellchecker that supports a wide variety of language and utilizes some AI functions. Similar to the propreitary software Grammarly.
- ### 🖥️ [Behave!](https://github.com/mindedsecurity/behave) 🐐
   *Gratis, Firefox Addons, Fully FOSS, Inactive*  
   A simple addon that monitors to see if webpages attempt several different types of attacks. If you never have a problem, it will never bother you.
- ### 🛜 [Bitwarden]([https://bitwarden.com/download/) 🐐
   *Gratis, Firefox Addons, Fully FOSS, Active, Default Permissions*  
   The official firefox addon for Bitwarden Password Manager. Allows you to easily autofill passwords into your browser.
- ### 🖥️ [KeePassXC-Browser](https://keepassxc.org/)
   *Gratis, Firefox Addons, Fully FOSS, Active*  
   The official firefox addon for KeePassXC Password Manager. Allows you to easily autofill passwords into your browser.
- ### 🖥️ [Buster](https://github.com/dessant/buster) 🐐
   *Gratis, Firefox Addons, Fully FOSS, Active*  
   An addon that attempts to automatically complete captchas for you.
- ### 🖥️ Bypass Paywalls Clean 🐐
   *Gratis, Sideloaded Addon, Fully FOSS, Active*  
   An addon that forecefully bypasses soft paywalls on websites. This was taken down both on the Firefox Addon store as well as Github, so it is hard to find safely nowadays and has no current official source. Be careful what you download.
- ### 🛜 [Chameleon](https://github.com/sereneblue/chameleon) 🐐
   *Gratis, Firefox Addons, Fully FOSS, Active, Default Permissions*  
   Allows you to spoof your timezone, user-agent, and more. Not useful for privacy, as it is easily detectable, but can get you past "Browser Not Supported" blocks and speed up websites that are made intentionally slow on Firefox (looking at you, YouTube)
- ### 🛜 [Dark Reader](https://darkreader.org/) 🐐
   *Gratis, Firefox Addons, Fully FOSS, Active, Default Permissions*  
   Allows you to force dark mode on all websites, with a blacklist toggle. Works very effectively, with it only rarely breaking websites. Can slow down the browser somewhat.
- ### 🖥️ [Flagfox](https://flagfox.net/) 🐐
   *Gratis, Firefox Addons, Fully FOSS, Active*  
   Allows you to see in your search bar the country that the server you are connecting to is on any given website.
- ### 🖥️ [Multi Account Containers](https://github.com/mozilla/multi-account-containers) 🐐
   *Gratis, Firefox Addons, Fully FOSS, Active*  
   An official Mozilla extension. Provides you with slightly better than default website isolation, and allows you to open a website in two different tabs with two different accounts at once.
- ### 🖥️ [Gesturefy](https://github.com/Robbendebiene/Gesturefy) 🐐
   *Gratis, Firefox Addons, Fully FOSS, Active*  
   Allows you to maneuver your browser faster using mouse-based gestures activated by holding down right click.
- ### 🖥️ [Joplin Web Clipper](https://joplinapp.org/) 🐐
   *Gratis, Firefox Addons, Fully FOSS, Active*  
   The official firefox addon for Joplin, the note-taking tool. Allows you to save websites into Joplin.
- ### 🛜 [LibRedirect](https://libredirect.github.io/) 🐐
   *Gratis, Firefox Addons, Fully FOSS, Active, Default Permissions*  
   Allows you to automatically open links for whitelisted websites in privacy-focused frontends. For example, open YouTube links in FreeTube.
- ### 🖥️ [Plasma Browser Integration](https://github.com/KDE/plasma-browser-integration) 🐐
   *Gratis, Firefox Addons, Fully FOSS, Active*  
   Official KDE Firefox addon. Provides better integration between Firefox and the KDE Desktop Environment.
- ### 🖥️ [Request Control](https://github.com/tumpio/requestcontrol) 🐐
   *Gratis, Firefox Addons, Fully FOSS, Inactive*  
   Allows you to selectively block specific HTTP requests, which you can use to block some third-party connections on websites you visit.
- ### 🖥️ [Side View](https://github.com/mozilla/side-view) 🐐
   *Gratis, Firefox Addons, Fully FOSS, Active*  
   An official Mozilla extension, that allows you to open websites in the browser sideview, and thus have two websites open side by side in one window.
- ### 🖥️ [Simple Tab Groups](https://github.com/Drive4ik/simple-tab-groups) 🐐
   *Gratis, Firefox Addons, Fully FOSS, Active*  
   Allows you to save groups of tabs under a name, which can be opened at any later time. Never lose a tab again.
- ### 🛜 [SingleFile](https://github.com/gildas-lormeau/SingleFile) 🐐
   *Gratis, Firefox Addons, Fully FOSS, Active, Default Permissions*  
   Allows you to download a website as an HTML file.
- ### 🖥️ [Snowflake](https://snowflake.torproject.org/) 🐐
   *Gratis, Firefox Addons, Fully FOSS, Active*  
   Turns your browser into a proxy which allows people in oppressed countries, where they can't access Tor, to connect to the network through your computer. Non-identifying and completely safe.
- ### 🖥️ [Tabliss](https://tabliss.io/) 🐐
   *Gratis, Firefox Addons, Fully FOSS, Active*  
   Allows you to edit your new tab page significantly, to make it exactly as you like.
- ### 🖥️ [Temporary Containers](https://github.com/stoically/temporary-containers) 🐐
   *Gratis, Firefox Addons, Fully FOSS, Inactive*  
   Uses the infrastructure of Multi Account Containers to open every new tab in its own container. Increases isolation between websites very slightly.
- ### 🛜 [Terms of Service; Didn't Read](https://tosdr.org/) 🐐
   *Gratis, Firefox Addons, Fully FOSS, Active, Default Permissions*  
   Allows you to see a human-readable version of the Terms of Service of every website you visit, as well as an A-E rating, all done by lawyer volunteers.
- ### 🛜 [uBlock Origin](https://ublockorigin.com/) 🐐
   *Gratis, Firefox Addons, Fully FOSS, Active, Default Permissions*  
   An amazing privacy addon which also blocks adds. Highly customizable, allowing you to replace almost all other privacy addons which one used to need.
- ### 🛜 [Under New Management](https://github.com/classvsoftware/under-new-management) 🐐
   *Gratis, Firefox Addons, Fully FOSS, Active, Default Permissions*  
   Warns you if any of your browser addons change ownership on the Firefox Addon store, so you can make sure it wasn't bought out by a shady company or something.
- ### 🛜 [Unpaywall](https://unpaywall.org/) 🐐
   *Gratis, Firefox Addons, Fully FOSS, Active, Default Permissions*  
   When you visit a paywalled article which is available for free legally on another website, it will notify you.
- ### 🛜 [Web Archives](https://github.com/dessant/web-archives) 🐐
   *Gratis, Firefox Addons, Fully FOSS, Active, Default Permissions*  
   Allows you to open a website in a variety of archival sites, such as the Wayback Machine, to see how it has changed over time.
- ### 🖥️ [XDM Browser Monitor v8+](https://xtremedownloadmanager.com) 🐐
   *Gratis, Firefox Addons, Fully FOSS, Active*  
   Connects with Xtreme Download Manager, to allow you to download things in it directly from your browser.
- ### 🖥️ [Zotero Connector](https://www.zotero.org/download/connectors) 🐐
   *Gratis, Sideloaded Addon, Fully FOSS, Active*  
   Connects with Zotero, to allow you to save websites with their metadata into Zotero directly from your browser.

# Search Engines
Websites which allow you to easily find websites and relevant information online through the use of keywords and phrases.

- ### 🛜 [SearXNG](https://github.com/searxng/searxng)
   *Gratis & Self-Hostable, No installation, Fully FOSS, Active*  
   A metasearch engine, which you can set up to search the results from other search engines, priotizing what exactly you want.
  
# Darknet Access
Apps that allow you to access the Darknet, including browsers and other apps.

- ### 🛜 [Tor Browser](https://www.torproject.org/) 🐐
   *Gratis, AppImage OR F-Droid Repository, Fully FOSS, Active, Default Permissions*  
   A browser built to minimize fingerprinting and reroute all traffic through the Tor Network. Also allows you to access .onion sites. DO NOT edit your browser in any way, shape, or form, outside of setting it to Safest mode or you will be fingerprintable. Extremely slow, but the absolute best for privacy.
- ### 📱 [Orbot](https://guardianproject.info/apps/org.torproject.android/) 🐐
   *Gratis, Guardian Project Repository, Fully FOSS, Active, Default Permissions*  
   Allows you to proxy apps to run all traffic through the TOR Network. Useful if you want to maximize privacy within a certain app or across your whole phone.
- ### 🛜 [I2P](https://geti2p.net/en/)
   *Gratis & Self-Hostable, CLI Installation OR F-Droid Repository, Fully FOSS, Active, Default Permissions*  
   Allows you to run a browser through I2P, allowing you to access eepsites.
- ### 🛜 [I2PD](https://i2pd.website/) 🐐
   *Gratis & Self-Hostable, AppImage OR F-Droid Repository, Fully FOSS, Active, Default Permissions*  
   A C++ Implementation of I2P, which allows you to do all the same things you can with regulat I2P.

# Phone Calling
Any app which allows you to actually use your Android phone as a phone. I know, shocking in this day and age.

- ### 📱 [Koler](https://github.com/Chooloo/koler)
   *Gratis, F-Droid Repository, Fully FOSS, Active, Default Permissions*  
   A simple Dialer app that gets the job done. No crazy features, just exactly what one would expect out of a dialer app.
- ### 📱 [Fossify Phone](https://github.com/FossifyOrg/Phone)
   *Gratis, F-Droid Repository, Fully FOSS, Active, Default Permissions*  
   A dialer app that, yet again, simply works. Fairly customizable.
- ### 📱 Phone
   *Gratis, GrapheneOS Default App, Fully FOSS, Active, Default Permissions*  
   The default GrapheneOS phone app. Works well, and even has a recording feature built in.

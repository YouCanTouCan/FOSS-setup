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

# Software Stores, Managers, and Finders
These are software capable of discovering other software and/or download other software. These recommendations can be used in tandem with one another to obtain most other apps on this list. 

- ### 🖥️ [Discover](https://apps.kde.org/discover/) 🐐
   *Gratis, Fedora 40 KDE Repository, Fully FOSS, Active*  
   The Discover store is the main store when using the KDE desktop environment. It allows you to install software from a wide variety of repositories, as well as search for software by category, and read reviews. Overall an effective software store.
- ### 🖥️ [Software](https://apps.gnome.org/Software/)
   *Gratis, Fedora 40 Gnome Repository, Fully FOSS, Active*  
   The main software store for the Gnome desktop environment. It allows you to install software from a wide variety of repositories, as well as search for software by category, and read reviews. Overall an effective software store.
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
DNS, or Domain Name System, can be likened to a phonebook - it basically tells your phone what website is what, and more. Full transparency, I'm fuzzy on the details.

- ### 🛜 [NextDNS](https://nextdns.io/) 🐐
   *Freemium, CLI only, Fully FOSS, Intermittent Development, Default Permissions*  
   A highly customizable DNS, allowing you to block specific ads trackers, and websites highly effectively device-wide.

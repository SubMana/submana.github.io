---
layout: posts
title:  "PkHex Tutorial"
date: 2017-02-02
tags: tutorials
---

So, I decided to do a little digging into what was possible with my Wii console (that had been gathering dust for several years at this point), and discovered a ton of old and most likely outdated tutorials for several different aspects of Wii Homebrew. I'm gonna continually update this article as I discover more cool things, so check back sometime.

# Prerequisites

The best and most concise tutorial on actually getting started with homebrew can be found [here](https://sites.google.com/site/completesg/hacking-guide/4-3-guide). It'll get you up and running with homebrew, the first step towards those cool games.

**Sidenote:** You'll most likely want to have a large Hard Drive (HDD) if you want to have a ton of 'backups' on hand, mine is 500GB but something like 320GB is usually recommended. An external Passport Drive works just fine for this, and can be found quite cheaply online or at any electronics store. An SD card CAN be used for this, but it requires quite a few workarounds to get working (such as installing a different cIOS) and I'm not going to cover that here. If you need help with it, please feel free to contact me.

Anyway, continue to [here](https://sites.google.com/site/completesg/backup-launchers/installation) to undergo the next step in hacking your Wii, cIOS installation. This basically allows you to enable the even cooler homebrew, such as the ever-coveted backup loader.

# I just wanna load my totally legal backups I got from emuparadise bro

lmao same

At this point, you'll need a certain program named 'Wii Backup Manager' to format your HDD to Fat32, as Windows usually formats it to NTFS by default. This program has other uses which I'll go into later, so grab it now from [here](http://www.wiibackupmanager.co.uk/) (I noticed that downloads were very slow, so if you're having issues getting it, e-mail me and I'll put up a mirror.)

In this program you can select your HDD from the 'Tools' dropdown, and then make sure you've selected Fat32 instead of wbfs (an outdated filesystem), and the cluster size is 32kb. Once that's complete, you're basically on your way!

Some tutorials will ask you to make a wbfs partition, these guides are outdated, Fat32 works just fine for 99% of people.

Download USBLoaderGX from [here](https://sourceforge.net/projects/usbloadergx/files/latest/download) and extract that 'apps' folder to the root of your HDD, and plug it into the left (or bottom) USB port of your Wii. Then, run the homebrew launcher (with your SD card no longer inserted) and you'll see this app in the list. Once you're in, you're free to install your discs (using the little plus icon on the far left of the USBLoaderGX menu) to the HDD and play them without having to insert them!

# Okay but what if I don't have the discs

Great question, and actually another reason we have Wii Backup Manager. Using this app you can install games downloaded from sites, and copy them to your HDD in a format that your Wii can easily understand. It's also possible to do this manually, but this program streamlines the process and makes it much easier.

# That's great but now I want Gamecube games

Sure, that just requires you to install a homebrew app called 'Nintendont', found [here](https://github.com/FIX94/Nintendont) (note that you'll need to download the files manually and put them in a folder named 'nintendont'). Once that 'nintendont' folder has been placed in the 'apps' folder, just extract the Gamecube discs like you normally would a Wii game and USBLoaderGX will handle the rest for you. To actually launch the games, go into settings -> loader settings -> GameCube Mode -> Nintendont.

# Conclusion

Gaining access to backups on your Wii is a surprisingly easy task still, so hopefully this guide helps a little bit in explaining the complex parts of other tutorials found online.



#### Contact submana@mail.com if any links are broken or you have suggestions for a better tutorial. This post was last edited: 2017/04/12.

---
title: "My Personal Love-Hate With Acer"
description: "A rant on how good and shitty the sw05-012 is"
pubDate: 2026-08-22
---

So at a flea market i bought a Acer Aspire Sw05-012 at a Flea Market for 20 Euro in Uknown condition. Got Home and Noticed the Originial Charger was snapped off in the cahring port, was a pain to get out and i used a spare fitting charger. Booted it up and it came preinstalled with Windows 8.1 for X86, not X66 / X86_64, because they cheaped out on using a 64-Bit UEFI. Tried getting Widnows 10 until i realised Acer doesnt Provide ANY Drivers for this thing and if even, It'll be a shitty 32-bit copy.

Linux wasnt any better. Arch failed to Instll, reason being after the latest package updates my SDIO Network Adapter want compatible. Fedora struggled booting the Live Env. Artix failed because no ia32.efi, basically only some distros do work. MX Linux worked the best so far but the desktop isnt my style. Debain almost worked but keeps defaulting to the bootx64.efi instead of bootia32.efi

the Device's battery live soemtimes is questionable beause one time t holds for days while at one moment it fully dies. May be from certain OSes previously and or failed installs. Im trying Debian 13, If even that fais i need to go back to MX-Linux. 

Apparently Debian 13 Dropped Support for 32-bit... and Debian 12 requires Secure boot off even tho i set it as trusted in the uefi

Even Debian 12 breaks, Cant connect to home network. On Hotspot it cant contact any mirrors.

i geniuenely hate this thing but when it did work it runs good like Android, back then Arch.

That's it bye
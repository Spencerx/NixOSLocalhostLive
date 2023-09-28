# NixOSLocalhostLive
Attempt at Offline Installer for @NixOS, Evaluating possible but working solutions. Expect a Gist!

This is an attempt ot update current or past efforts from this semester because they look too academic unless you have tested and tried them with success.
Basically most installers in the recent past are not offline installers for most operating systems.

Most system admins only really use offline installers especially those working in a data center. So in certain places it may 
be reality that my pipe to the machine or any other ddevice will be more than a certain data center has. 
Just a note to keep in mind.

The whole note is here https://sourcegraph.com/notebooks/Tm90ZWJvb2s6MzA5OQ==
The complete text is right here:
From here https://termbin.com/kexo9
To this 
Personal Notes:

My first linux experience personally is from Mandrake and Slackware, even had a HP Mandrake CD coming from another classmate doing system admin, in a class it's always nearly RedHat isn't it especially counting backwards until you get to now however you count with the stats at hand. Let's be clear my first real computing experience will always remain Unix we had Xenix(yes MS) then CP/M DOS, Win 3.11 et cetera apart from the home Amigas, Amstrads, Ataris, BBC Micros, Commodores, Generics & Spectrums. Apropos.
In those days you had to have all things on a disc(the only floppies I have are about haradio hardware today. Look at your mobile and tablet, some of us such as myself refuse to use them on the basis that it's just another weight to carry unless it has a dedicated role living up to it but on a computer you can make up for lack of a continous connectivity the same way you used dialup - some still do just like packet radio from 600 baud to whatever your hardware supports. There's error correction but let's focus on that as debugging here added to the lifecycle of your use of any device with some software which doesn't have auto correct at all. Subject to your input you get a acceptable level of correction amd compensation with the right framework. 

The social value of this comes from the question of availability - translation in realtime means value you can measure, as any road warrior will know that keeping a connection going is not stitious but you have to run up and down to a specific site to keep a connection, so away from a blazing fast 5G or nearly 5G like WiFi I'll depracate this from that, to a typical 4G connection which is the norm for most people in large land mass apart from over crowding on smaller land mass, block  or any  structure, distribution is a persistant question that does not care for a consitent connection and updates when you need a device to live up to it's sole purpose unless you are willing to go all out on definitions on the basis of a general purpose operating system. On this typical connection you have one or two bars as long as you are mobile, from experience you will know zero bars from real travel. So it's necessary to see the value from a few pixels to gigabytes of them. So apart from whatever you can imagine we can visualise source trees and see the cause and effect overtime from the beginning of 60s Unix to now in relation to development. 

Inspiration stems from my past experiences with OpenSUSE in the last decade or so but this was motivated by a friend from Austria and in a class to share discs with other students all from memory - the question wasn''t how but when not if, as a teen the thing is when you can see the obvious future when most things are coming in from the web and stored on the web the catch twenty two is always getting the source, binaries and synching that with all you need to do on your machine(s) at you usually call localhost. In the last decade I managed to distibute some discs as far as Namibia but being online the best partner is your imagination and going postal, yes not just the pun before that takes of in a loop - the post office like your mailer daemon. It comes from another localhost, always.


Some of this stems from a question posted by on NixOS https://discourse.nixos.org/t/any-possibility-of-purely-offline-gui-installer-iso/31254

NixOS Links
On point creating for Offline first https://nixos.wiki/wiki/Creating_a_NixOS_live_CD

Creating a CD/DVD image https://github.com/NixOS/nixpkgs/blob/master/nixos/modules/installer/cd-dvd/iso-image.nix

Another Question with answers on stack https://stackoverflow.com/questions/45037890/install-nix-packages-offline

Curated Topic 
https://www.libhunt.com/posts/1005316-offline-installer-with-flake

Auto Install of Nix with a hard drive wipe out warning
https://gitlab.com/kevincox/nixos-auto-install

Other Links Like OpenSUSE basically building images or packages using OBS & KIWI
The main link is SUSE Studio Express not https://studioexpress.opensuse.org/
Building OS ISO Images for OpenSUSE/SUSE related images just as we did with SUSEStudio.com https://youtu.be/Zy3ZjvQuzUs?si=LnN1yRhaxsACZBTT
Building CentOS https://youtu.be/RKeFR4R2IeA?si=AOXjJy06tf8qFnao 
Other hints for other flavours of Linux https://youtu.be/EHkgqimhl5o?si=-u5qE1bU--eRdvx
Subject to more input there's no reason why NixOS shouldn't benefit from KIWI & OBS since you can run nix and do some CI builds on it. Another approach.

Don't go to the fail spot https://sourcegraph.com/notebooks/new


https://gist.github.com/Spencerx/bb55db6f9a92bed686dd6107eff2fb5c.js
  
I was working with @dotFiles's configuration earlier in the day.
https://github.com/pca006132/dotfiles/blob/master/installer-configuration.nix
These are the suggestions based on ealier versions of NixOS not the current version Stoat(Public release date May, 2023) 
by @tfc https://github.com/tfc/nixos-offline-installer here's a digest of another user looking for offline solutions. https://www.libhunt.com/posts/1005316-offline-installer-with-flake


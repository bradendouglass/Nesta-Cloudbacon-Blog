---
title: Infinity Keyboard
date: '2015-04-05'
---

As an avid keyboardist, keyboarder... whatever. I jumped on the very first [Inifinity Keyboard][1] offered by Massdrop back in November of 2014. Having built it, played with it and attempted to program it with a missing web interface; there is definitely more than a few words on my mind. However, this post is more of an introduction to the knowledge gained throughout my time with it, instead of a true review/product breakdown. [GitHub houses a random collection of markdown files][2]. [One specifically][3] highlights ways to build/config/customize the Infinity's layouts.

Hopefully this helps folks out who are struggling with the seeming lack of information surrounding this obscure but, somewhat interesting [way to define keyboard layouts][4]. If for any reason you happen to want to add or correct anything, feel free to open a GitHub issue.

One last thing: There seems to be a lot of talk surrounding the bounce/debounce rate of these boards. Some of them seem to exibit double key presses from one single keypress. While this is a configurable option in the KLL files, it should not be a need if the board was properly soldered. A very easy fix is to flux/solder the connections up with quality 60/40 rosin core solder.

### Update 2015-04-12

I have finally compiled all of the build scripts into one KLL based directory that could be wrapped in Git. The [Git repo is, as always on GitHub][5] and everyone should fork it if they are looking for a quick way to bootstrap their Infinity based Keyboard.

In other news, the awesome folks at Massdrop have [released an ErgoDox keyboard][6] variant that will be powered by the same configurator/keyboard mapping language. The great thing about these keyboards using the same controller is only needing to have one [workman-p mapping][7] that can be flashed to different keyboards. Which means, although I own and adore my now gen1 ErgoDox, I will definetly be picking up the new version. Likely with stiffer, Cherry MX Tactile Greys.

[1]: https://www.massdrop.com/buy/infinity-keyboard-kit
[2]:https://github.com/braidn/Knowledge-Repo
[3]: https://github.com/braidn/Knowledge-Repo/blob/master/InfinityKllInfo.md
[4]: https://www.overleaf.com/read/zzqbdwqjfwwf
[5]: https://github.com/braidn/infinity
[6]: https://www.massdrop.com/buy/infinity-ergodox
[7]: https://github.com/ojbucao/workman

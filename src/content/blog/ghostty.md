---
title: 'First impressions on Ghostty'
description: 'Title explains. First impressions on Ghostty.'
pubDate: 'December 30 2024'
updatedDate: 'December 30 2024'
---

So far, Ghostty is very featureful whilst being very performant. Also, because Ghostty uses native libraries (GTK, and whatever MacOS uses) for their UI, it has this [native feel](https://gpanders.com/blog/ghostty-is-native-so-what/) on MacOS or GNOME. Also, tiling WM users can disable the window decorations to get a cleaner UI, which I'm doing at the moment with Hyprland.

Also, it has pretty much perfect (Nerd) font support, where support on Foot was lackluster.
Kovid, the developer of Kitty has been conservative about adding features to the terminal, which is understandable, but... It doesn't have some of the features I wanted! Which is really the only downside of Kitty but Ghostty solves with some useful features.

Performance-wise, both [Kitty](https://github.com/kovidgoyal/kitty/issues/7005) and [Ghostty](https://mitchellh.com/writing/ghostty-devlog-006) uses SIMD for its VT parser (or so I believe) which makes it really fast. Alacritty is the fastest in theory but at the same time, [it's really not fast(er than Kitty)](https://github.com/kovidgoyal/kitty/issues/2701#issuecomment-636497270).  One downside is that Ghostty starts up slower than Kitty (with `-1`), ST or Foot but, Mitchell notes this isn’t a big issue, as most users spend their time working in the terminal rather than frequently opening and closing it, unlike [r/unixporn](https://www.reddit.com/r/unixporn/) users (don't worry, the sub is healing).

Feature-wise, I've yet to explore most of the features but, at first glance, it seems to have all the features I wanted—and even some I didn’t realize I needed (and still don't). It has shaders, automatic shell integration, tabs, the native feel (as stated above), essentially perfect font support, Kitty image protocol and much more. According to the [roadmap](https://github.com/ghostty-org/ghostty?tab=readme-ov-file#roadmap-and-status), it doesn't have all the "fancy features" but, it is something that's being worked on so it's not much of a biggie.

But, other than that, it's not really interesting. It's just a terminal, it hasn't revolutionized how I work in the terminal (it did cure cancer and solve world peace, but who cares about that lol), but rather a drop in replacement for most terminals. But, it does all the things I want a terminal to do, so maybe it is the best terminal, maybe behind Kitty. Which is good for a 1.0 release (it didn't really live up to its hype though. Typecraft really did a good job hyping it up.). 

This is a great [stable base](https://changelog.com/podcast/622), as described by Mitchell Hashimoto, who says is planning to really change the terminal world in the form of "technology philanthropy" which is a noble cause :).
It'll be very interesting on where Ghostty will take the terminal land to, hoping this will make change for the better.

# EDIT (2024/12/30)
Apparently, Ghostty doesn't look nice on KDE. Expected as Ghostty is written in GTK but it'll mena it's not truly cross-platform (albeit, good enough). 

---
layout: post
title: "Useful tools/settings for Linux"
tags: [notes]
finished: false
---

Since 2020, I have switched to use Linux as my main working environment. I have gradually accumulated some useful tools that made Linux run smoothly for me. Also, there are other things that are just very good to know. 

## Text replacement

MacOS has an easy way to set up text replacement. This is useful for occasional math-related notations and correcting typos. While Windows must have a way to make this work too, I never figured to find a way to do so. On Linux, surprisingly easily, [Espanso](https://espanso.org/install/) ended up working well. One `config.yml` covers most things I can think of. I also tried AutoKey for a while, but there is an unresolved bug that seem to remain as an unresolved issue on the original repo (which doesn't seem to be maintained much anymore).

## Mouse key mapping

In MacOS or Windows, with which mice are typically manufactured in mind, remapping these keys to certain commands (e.g., volume up/down, copy/paste) is often inherent in the system settings. In linux, it can be achieved by using `xvkbd`. 

## Input method

This was a major pain back when I was using MacOS. My particular need on input methods is that I need to be able to switch between a couple languages at the same time, and the "switch to the next input method" keybinding always requires me to press it once, see if it has changed to the desired input method, and if not, keep repeating this process until it does. This process annoys me for some unknown reason, and all I want is a method to switch to a particular input method without needing to look and check. [Rime](https://rime.im/download/#linux) has been awesome in supporting different types of Chinese (Simplfied AND Traditional), as well as other orthographies such as Japanese, Korean and IPA. I did not go for this when I switched to Rime, but turns out it's also useful in typing symbols such as ℃ and § (if you ever need to). It's also practically programmable, thus allowing me to waste hours of time on the config file. 

## Reference Manager

I have been using Mendeley since I started to have the need for a reference manager. Mendeley also worked back when I used Ubuntu-based Linux. However, since I switched to an Arch-based OS, Mendeley continued to have a bug with its display that any paper opened inside of Mendeley is blurry. This bug is fixed now, but during the months that Mendeley is unusable, I have found `papis`, a [command-line reference manager](https://github.com/papis/papis) that, once correctly configured, is very powerful and easy to use. Searching for and pulling up a paper is also faster than the Mendeley GUI.  

## Slides, presentations

I have been going back and forth with Google Slides and LibreOffice Impress. Neither is perfect and I might have just gotten used to the inherent software in MacOs over the years (especially in college, when I had to wrap up presentations in under an hour -- good times). However, for LibreOffice Impress, there are a few tweaks that might make things easier. For example, disabling `Allow quick editing` ([reference](https://ask.libreoffice.org/t/cant-select-text-box-in-impress-to-move-it/60954)) can make editing easier, since one can then drag textboxes around without going into the editing interface all the time. 

## Music

I use `Quod Libet`, because the name is in Latin and I couldn't help it. It goes well with the tag editor `Ex Falso`. However, Ex Falso seemed to be able to do everything _but_ to change album cover photos. Therefore I also have `EasyTag` to do that for me. 

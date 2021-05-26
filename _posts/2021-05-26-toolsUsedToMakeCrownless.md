---
layout: post
title: "Tools Used to Make Crownless"
tagline: "They're all open source!"
categories: crownless 
image: /assets/blog_images/crownless_flippers.gif
permalink: "blog/tools-used-to-make-crownless"
---
[Crownless](/crownless) is made using open source tools, here is a list of them.

<div style="text-align:center"><img src="/assets/blog_images/crownless_flippers.gif" width="40%" /></div>

### Main Tools

* __Framework__ -- [LÖVE](https://love2d.org/) (aka Love2d). Love2d is an open-source cross-platform framework which uses [Lua](http://www.lua.org/) as it's scripting language. The code for Crownless was written in Lua.<br/><br/>
While Love doesn't have an IDE and therefore requires a lot of code writing, it allows for a lot of freedom on what can be made. It has a very great active community both on the [forums](https://love2d.org/forums/) and the Discord channel.<br/><br/>

* __Art__ -- [Aseprite](https://www.aseprite.org/). Aseprite is a fantastic tool designed specifically for pixel art. I tried a few other tools before using Aseprite, and found Aseprite to be much better for making 2d pixel art.<br/><br/>
You can pay $20 for Aseprite on Steam, or you can even [build it from source code](https://geoff.tuxpup.com/posts/aseprite_on_fedora/) for free.<br/><br/>

* __Levels__ -- [Tiled](https://www.mapeditor.org/). Tiled is a powerful 2D level editor, which has lots of extra features. It can export .lua files, which can feed directly into Love2d via the [STI](https://github.com/karai17/Simple-Tiled-Implementation/blob/master/tutorials/01-introduction-to-sti.md) library. 

### Other
* Android -- To test the game on mobile, the [Love2d Android app](https://play.google.com/store/apps/details?id=org.love2d.android&hl=en_US&gl=US) can be used together with [Termux](https://play.google.com/store/apps/details?id=com.termux&hl=en_US&gl=US) and git for quick updates and testing of changes. For compiling APKs, Android Studio was used with [love-android](https://github.com/love2d/love-android) the Android port of Love2d.
 
* Coding Environment -- Linux was the operating system, Vim was the code editor, and Git was used for version control.



<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

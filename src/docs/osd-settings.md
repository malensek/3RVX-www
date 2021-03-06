---
title: 'Settings - OSD'
---

OSD Settings
============
These settings control OSD (on-screen display) functions. OSDs are visual notifications that appear on the screen for a period of time to convey information, such as the current volume level.  Each OSD also supports "notification icons," also commonly known as "tray icons" that appear near the clock in the Windows taskbar.

Jump to an OSD:

* [Volume](#volume)
* [Eject](#eject)
* [Brightness](#brightness)
* [Keyboard](#keyboard)


Volume
------

Subscribe to system volume events
: Detects changes to the system volume level by other applications and displays the volume OSD when the changes occur. For example, changing the built-in Windows volume slider will cause the 3RVX OSD to display. If this is disabled, then the OSD will only be displayed when using 3RVX-based hotkeys.

Device Selector
: 3RVX normally monitors the system default audio output device, but a specific output device can be selected here.

Audio Taper Selector
: Volume is measured in decibels (dB), a logarithmic (nonlinear) scale. In other words, adding 5 dB to the system volume has a different effect on output loudness depending on the current level. To make an easy-to-understand volume slider ranging from 0 -- 100%, most operating systems apply an *audio taper* to the logarithmic volume curve to make it behave more like a linear scale; adding 5% to the volume level should increase the output loudness by roughly the same amount.

<figure>
<img src="volume-curves.png" alt="Volume Curves" width="350px">
<figcaption>Volume taper levels from a sample hardware configuration. The default taper increases the volume level quickly on the low end, but slows near the high end. On the other hand, a custom taper of 8 inverts the curve.</figcaption>
</figure>

Volume Limiter
: This option prevents 3RVX from raising the volume past a specified limit. Note that when this option is applied, the limit becomes the new "100%" volume level as reported by 3RVX.

Force volume limit
: Forcing a volume limit prevents changes that occur outside 3RVX (other applications, the system volume slider, etc). This is achieved by detecting changes above the limit and resetting the volume level.

Mute volume during session lock
: When enabled, 3RVX will mute the volume when the current session is locked (accessed from the start menu or by pressing Win+L).


Eject
-----


Brightness
----------


Keyboard
--------



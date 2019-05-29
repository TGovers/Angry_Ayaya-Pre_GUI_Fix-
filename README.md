# ANGRY AYAYA

**DO YOU LIKE ANIME? DO YOU LIKE MEMES? DO YOU OCCASSIONALLY PARTAKE IN AUDIO CREATION WHERE YOU DESPERATELY NEED AN ANIME-THEMED PLUGIN???** 

**DON’T LIE MY FELLOW ~~WEEBS~~ ANIME ENTHUSIASTS, WE KNOW YOU DO AND _BOY OH BOY_ DO WE HAVE THE PRODUCT FOR YOU!**

### /// INTRODUCING ///
### /// ANGRY AYAYA ///

![alt text](https://i.imgur.com/BVEH52G.png "Ayaya")

## Table of Contents  
[Angry Ayaya TLDR](#angryayayatldr)

[Installation Guide](#installation-guide)

[Angry Ayaya In-depth](#angry-ayaya-in-depth)

[Contributing](#contributing)

[License](#license)

<a name="angryayayatldr"/>
<a name="installationguide"/>
<a name="angryayayaindepth"/>

## Angry Ayaya TLDR

Angry Ayaya is a simple and intuitive VST plugin with an anime aesthetic. It utilises a 2-parameter IRR filter and a 4-parameter Distortion. Angry Ayaya was designed for use with a multitude of different instruments in mind, such as
* Synths
* Baritone Electric Guitars
* 7/8 String Electric Guitars
* Bass Guitars
* And anything else you want to put through it, it's completely up to you!

Angry Ayaya has full automation and save state capabilities for easy use within your favourite DAW! Currently Angry Ayaya only has a mac DMG installer, but can be used on Windows via the instructions listed here.

Angry Ayaya was inspired by the internet meme “Ayaya”, click the link to the Youtube video below to witness the majesty that is Ayaya 

<a href="http://www.youtube.com/watch?feature=player_embedded&v=9wnNW4HyDtg
" target="_blank"><img src="http://img.youtube.com/vi/9wnNW4HyDtg/0.jpg" 
alt="Ayaya Intensifies" width="240" height="180" border="10" /></a>

We created the plugin with the mindset of making a great-sounding plugin first and foremost, with a visually-appealing aesthetic following that. 

We really hope that you enjoy our plugin and make some awesome tunes with it!
Thank you!

-- Team Angry Ayaya --

## Installation Guide

For Mac users, we recommend cloning/downloading the repository to your computer and installing the plugin through the easy-to-use DMG installer

For Windows users, you will need to setup and run the plugin on your computer. For this you will need
* [Projucer](https://juce.com/ "https://juce.com/")
* [Microsoft Visual Studio](https://visualstudio.microsoft.com/ "https://visualstudio.microsoft.com/")

Please refer to a youtube guide in setting up these programmes if you are unsure! We recommend this video.

## Angry Ayaya In-depth

Angry Ayaya was built with Projucer(add link)/XCode(add link) as a plugin suited specifically to those who maybe don’t know their way round plugins, but are wanting something cool and intuitive to add that extra “oomph!” to their work. It utilises an always-active low-pass IIR filter and an optional distortion. IIR filters stands for an Infinite Impulse Response filter, which is unique with how the decay never really reaches zero (to put it simply!). We choose to use this as we personally thought it sounded the best out of the different kinds of filters that we tested. 

The IIR filter has two parameters that you can change; the frequency Cutoff and the Q-Factor. 
* The Cuttoff knob changes the maximum frequency that the filter will let through (as a low-pass filter)
* The Q-Factor knob changes the resonance or **Q** of the filter

The Distortion feature has four parameters that you can change; the Drive, Range, Blend and Volume. 
* The Drive knob changes the overall drive of the distortion (how "grunty" it is, to put it simply)
* The Range knob changes the overall frequencies of the distortion
* The Blend knob changes the blend between the distortion and the pre-distortion sound (ie the pure audio with just the IIR filter affecting it)
* The Volume knob changes the overall volume of the plugin (**this affects the whole plugin** and is used even if you "turn off" the distortion)

If you want to essentially “turn off” the distortion, just turn the distortion Drive, Range and Blend knobs to their lowest values. This is how it would look:

Here is a setup that we recommend to get you started with the plugin. It creates a really subtle distortion with just the low frequencies coming through, creating a nice rumble or pulse depending on what you are putting through it.

## Contributing

Currently Angry Ayaya is not open to contribution, but this could change in the future!

## License

MIT

# Trailmakers-autosplitter
An autosplitter is a tool used to automatically time segments of a run, this is a short tutorial on how to set one up for your Trailmakers run (currently only for Pioneers).

## Getting set up
### Necessary downloads
- LiveSplit\* ([main page](https://livesplit.org/), [download](https://livesplit.org/downloads/), [tutorial](https://youtu.be/L2cfeN9xHjM?si=TMh-gfRLAgn6uewD))
- AutoSplit ([main page](https://github.com/Toufool/AutoSplit?tab=readme-ov-file), [download](https://github.com/Toufool/AutoSplit/releases/latest), [tutorial](https://github.com/Toufool/AutoSplit/blob/main/docs/tutorial.md))
- Autosplit images folder in your resolution\*\* (File above)

\* Other split programs will probably work, but LiveSplit is the standard.

\*\* If these aren't available, read how to make them yourself [here](https://github.com/neut1729/Trailmakers-autosplitter/blob/main/README.md#making-your-own-autosplit-images) Images in a different resolution might work, as i haven't tested that, but i wouldn't count on it.

### Program setup
1. Open LiveSplit and follow the tutorial to set it up however you want, but make sure you turn on global hotkeys (in `Settings`).
2. Open AutoSplit and set the same hotkeys as you used for LiveSplit (in `File -> Settings -> Hotkeys`).
3. Select your Split image folder, either by pasting the file path into the provided textbox or by using the `Browse...` button.
4. Open Trailmakers, press the `Select Window` button, and click on the trailmakers window.

If there are any splits you do not want, remove them from the Split image folder.

You should now have a functioning timer that automatically starts, pauses during loads, splits, and stops at the end.

## Using the programs.
Using LiveSplit and Autosplit is fairly straight forward: Open Trailmakers and both timing programs, check if you have the right splits loaded in LiveSplit, check if AutoSplit is capturing Trailmakers and the images are loaded. If everything is in order you're ready to start your speedrun.

## Making your own autosplit images.
To make your own autosplit images you'll need an image editing program to make them partially transparent, i recommend Krita ([download](https://krita.org/en/download/)) since it's free and decently easy to use.
All screenshots need to be in the same resolution and preferably made the AutoSplit program. The images you need are:
- A screenshot containing "Oh, you're finally awake!" textbox with everything other than that text being transparent.
- A screenshot of the loading screen after exiting the cave, plus two copies of this image.
- A screenshot of you leveling up after first talking to tenso (preferably with the experience bar fully filled) with everything but the green bar being transparent.
- A screenshot of the explosion of one of the megadrills with everything but a rectangle near the bottom being transparent (look at one from the already provided files for reference), plus two copies.
- A screenshot of the "congratulations" screen.

Name all these images according to the naming scheme from the already provided files, and you should have working autosplit images.

***If you do make these, please send them to me so i can add them to this page.***

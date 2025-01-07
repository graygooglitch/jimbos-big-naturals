# Jimbo's Big Naturals (a Balatro mod)... now on 2.0!

<img src="https://i.imgur.com/GqlqXjt.png" alt="A banner saying Jimbo's Big Naturals with some Balatro card art but all the jokers have boobies.">

Jimbo's Big Naturals is a simple edit of Balatro's existing assets to give the jokers boobs. It is not intended to be a "gender swap" mod, though you may view it as making the jokers ladies if that pleases you. It is just the existing jokers, but now they have boobs. I made it myself using Aseprite.

It covers 122 of the 150 Jokers in Balatro. Other places where Joker imagery appears (such as wax seals, booster packs, and the Wraith spectral card) are also affected.

## Why?

I don't know. Sorry.

## This mod is SFW?! (for streaming purposes and whatnot)

That's right. No nipples are onscreen. The closest thing to anything scandalous is that Half Joker has a bare chest, but it's torn too badly so that it obscures anything of note. If you'd like to double check, you can open the various PNGs within the mod folder.

# Installation

This mod does not require any modloaders or anything - installing it is very simple. It's just a zip, some folders, and some PNG files (images). Balatro is built on a simple platform, and so you can open its EXE file like a ZIP file to view its internal files... and replace them too! That's how the mod is installed.

**You will need 7zip**, or a program with similar capability to open non-zip files as zips. <a href="https://www.7-zip.org/">Download 7zip here.</a> Fortunately, 7zip is free open source zip software.

## Windows

1. <a href="https://github.com/prettypinkpansy/jimbos-big-naturals/releases/latest">**Download BigNaturalsMod.zip** from the latest releases here</a>.
2. **Navigate to your Balatro installation folder.** This is probably something like `C:\Program Files (x86)\Steam\steamapps\common\Balatro`.
3. **Extract BigNaturalsMod.zip.** You should have a folder in your Balatro directory now.
4. **Right click on `Balatro.exe` in your Balatro installation folder**. A reminder you'll need 7zip or similar for this. You may need to click "Show more options" on later versions of Windows. Under the options it should say 7zip. Hover over it to reveal some options.
<img src="https://i.imgur.com/Z9TwkB8.png">

5. Under 7zip click **Open archive**.
6. Go into the **BigNaturalsMod folder**. Grab the **resources** folder and drag it over into your 7zip window, as shown below.

<img src="https://i.imgur.com/BC0oWfI.gif">

That's it! If you'd like to uninstall the mod, the "original files backup" folder in BigNaturalsMod has a resources folder with the original jokers. Just repeat steps 4 through 6 with that folder instead.

## Linux

1. <a href="https://github.com/prettypinkpansy/jimbos-big-naturals/releases/latest">**Download BigNaturalsMod.zip** from the latest releases here</a>.
2. There isn't a 7zip GUI for Linux, but this script does the same thing as the Windows steps. Edit the variables and run the following (you'll need the command line version of 7zip from your distro's package manager, e.g. `sudo pacman -S 7zip` for Arch):
    ```bash
    #!/bin/bash
    BIG_NATURALS_PATH=~/Downloads/BigNaturalsMod.zip # Or wherever you downloaded the release to
    BALATRO_PATH=~/.local/share/Steam/steamapps/common/Balatro # Or wherever you have Balatro installed
    INSTALL=true # Or false, if you want to uninstall the mod


    rm -rf /tmp/big-naturals
    7z x -o/tmp/big-naturals $BIG_NATURALS_PATH && 7z a $BALATRO_PATH/Balatro.exe "/tmp/big-naturals/BigNaturalsMod$(if test \"$INSTALL\" != \"true\"; then echo '/original files backup'; fi)/resources"
    rm -rf /tmp/big-naturals
    ```

## Mac

I don't have experience with this platform, sorry :( Hopefully you can find some way to open the Balatro exe and follow the steps above.

# I want to look at the boobie jokers without downloading the mod. Can you put the art here?
Sure can! **Spoilers for Balatro**, though - it's all the jokers in the game!
<details>
  <summary>Click this to view spoiler</summary>
  
  <img src="https://i.imgur.com/fc68i4C.png">
  
</details>
As of 2.0, there are also some additional touches. The wax seals, for instance, which feature jokers, have big naturals as well.

That's it! Thanks for checking this out! If you have any questions, comments, concerns, bug reports or bug facts, hit me up on <a href="https://bsky.app/profile/prettypinkpansy.bsky.social">Bluesky</a>.

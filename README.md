### Hello 👋!

I don't really like emotes so that wave will be the first and the last.

<!-- and I also hate markdown... >:( -->

My name's Nik, or Nikita Krapivin if you prefer boring legal names, I speak English and Russian, my timezone is UTC+05 or MSK+02.

I'm 17 years old, my current occupation is doing console ports. I (currently) study at [PMK](https://pmkedu.pro)

# How to reach me

- Discord: nik (octothorpe) 5351
- E-Mail: basically the email I use for my git commits, well, alienoom (the at symbol) yandex (dot) ru
- Twitter: (at) nkrapivindev
- GitHub: you're here!
- VK (Russian only please): (at) nkrapivindev

I'm also present at some Discord servers related to GameMaker research like Underminers and the GameMaker Kitchen.

Oh, right, here's a list of my activities, boring adults call this a CV:

## Console Ports!

- [Wally and the FANTASTIC PREDATORS](https://www.coolasheck.com/)

    My first ever commercial console port! Out on Xbox One/Series (back compat), PlayStation 4/5 (back compat) and the Nintendo Switch.
  
    Uses [Kotfile](https://github.com/nkrapivin/kotfile) for saving and [NekoPresence](https://github.com/nkrapivin/NekoPresence) for Discord Rich Presence.
  
    The leaderboards and cloud save servers for the VK Play version are powered by [Kotodoski](https://github.com/nkrapivin/kotodoski) and [Deta Space](https://deta.space).
  
    Made with GameMaker.

- [Space Scavengers](https://store.playstation.com/en-us/product/UP5464-CUSA32885_00-3922659958247696)

    A pretty simple game that I ported to PlayStation 4/5 (back compat) in a few weeks, has PSN leaderboards and trophies.
  
    Uses [Kotfile](https://github.com/nkrapivin/kotfile) for saving.
  
    Can't say much else about it, it's just a simple game.
  
    Made with GameMaker.

- [Deep Space Shooter](https://www.nintendo.com/store/products/deep-space-shooter-switch)

    Ported for Valkyrie Initiative to the Nintendo Switch.
  
    Made with GameMaker.

- [Hunahpu Quest. Mechanoid](https://www.nintendo.com/store/products/hunahpu-quest-mechanoid-switch)

    Ported for Valkyrie Initiative to the Nintendo Switch.
  
    Made with Unity. My first ever experience with this engine, actually.

- [Stones Keeper](https://www.nintendo.com/store/products/stones-keeper-switch)

    Ported for Valkyrie Initiative to the Nintendo Switch (Xbox One planned in the far future).
  
    (Was?) Made with a custom engine in C++ and Windows's OpenGL (WGL), also Audiere as the audio backend.

    I integrated the SDL2 library for controls, saving and pretty much everything. This worked well on the Switch.

    (Thanks to Ryan "icculus" C. Gordon, Ethan "flibitijibibo" Lee and many others for maintaining the Nintendo Switch port of SDL2!!)

    Then I replaced the Audiere backend with mojoAL since Audiere is licensed under LGPL and I couldn't use it on the Switch.

    After all of my changes I was also able to run this game on the Xbox One with relative ease,

    however, some things in SDL2 for GDK were not implemented, so I [implemented](https://github.com/libsdl-org/SDL/pulls?q=is%3Apr+author%3Ankrapivin) them and contributed my code back.

    Overall this was the coolest projet to work on, looking forward to more Xbox/GDKX stuff.

- [The Excrawlers](https://www.nintendo.com/store/products/the-excrawlers-switch)

   Ported for Valkyrie Initiative to the Nintendo Switch.

   Had to tweak the controls a little, and also saving.

   Made with GameMaker.

- [The Sin](https://www.nintendo.com/store/products/the-sin-switch)

   Ported for Valkyrie Initiative to the Nintendo Switch.

   My first ever Ren'Py port!

   This is a kinetic visual novel with no interactions and the default Ren'Py UI,

   so it was a good first candidate for porting, which also proved that my port passes Lotcheck.

- [Athanasy](https://www.nintendo.com/store/products/athanasy-switch)

   Ported for Valkyrie Initiative to the Nintendo Switch.

   My second Ren'Py port! This time a more complex VN.

   Thanks to the original dev team for helping out with art assets.

 - [OMNIMUS](https://www.nintendo.com/store/products/omnimus-switch)

   Ported for Valkyrie Initiative to the Nintendo Switch.

   My third Ren'Py port! This time with video playback and system on-screen keyboard integration.

   Thanks to the developer for providing all the art assets to our team and being very helpful in general.

- [Mondealy](https://www.nintendo.com/store/products/mondealy-switch)

  Ported for Valkyrie Initiative to the Nintendo Switch, Xbox One + Series X|S + PC (Xbox Live), GOG (Galaxy SDK), VK Play (Fume) and Linux (Steam Deck)!

  (PlayStation 4/5 and macOS coming soon hopefully...)

  The biggest porting project so far! Also uses [NekoPresence](https://github.com/nkrapivin/NekoPresence) for Discord Rich Presence on PC.

  Denis is very cool I hope you have a very awesome life!!!

## Native extensions for GameMaker

- [NekoPresence](https://github.com/nkrapivin/NekoPresence)

    This is an open source wrapper around Discord's rich presence library for GameMaker.
    
    It's used in many games, for example [Mondealy: Day One](https://store.steampowered.com/app/1591570/Mondealy_Day_One/), [Vividerie](https://store.steampowered.com/app/1769200/Vividerie/), [MAKE ME REAL](https://asire.itch.io/make-me-real) or [Wally and the FANTASTIC PREDATORS](https://store.steampowered.com/app/1077450/Wally_and_the_FANTASTIC_PREDATORS/).

- [GMESCAPI](https://github.com/nkrapivin/GMESCAPI)

    This is a fork of the ESCAPI webcam library that adds GameMaker support, so yeah, this is a webcam extension for GameMaker.
    
    Sadly I don't know of any public games that actually use it, maybe because it's kinda spooky to take pictures from the webcam nowadays? Who knows.

- [libmulti](https://github.com/nkrapivin/libmulti)

    This is a library to create and manage multiple windows from GameMaker, very useful for in-game tools like level editors or whatnot.
    
    It's using Direct2D for rendering and accepts GML surfaces as canvases.

## GML libraries for GameMaker

- [Kotfile](https://github.com/nkrapivin/kotfile)

    This is a callback-driven library for easy asynchronous file operations in GameMaker.
    
    Very important if you're porting a game to consoles and want to pass certification.
    
    Right now Kotfile is used in [Wally and the FANTASTIC PREDATORS](https://store.steampowered.com/app/1077450/Wally_and_the_FANTASTIC_PREDATORS/)

- [BnvibCrap](https://gist.github.com/nkrapivin/6ae530e8b017bb48d78511f7514c1f09)

    A small 'audio player'-like class for Nintendo Switch HD Rumble files (aka .bnvib).
    
    It has the ability to play, stop, pause and rewind bnvibs, it also allows to play looping bnvibs that have loop points assigned in them.
    
    It's also used in [Wally and the FANTASTIC PREDATORS](https://store.steampowered.com/app/1077450/Wally_and_the_FANTASTIC_PREDATORS/).
    
- [gmlUPnP](https://github.com/nkrapivin/gmlUPnP)

    A pure-GML implementation of the UPnP protocol, very useful if you want to do automatic port forwarding in a multiplayer game on a compatible router.

- I also made workarounds for some issues with the new Steamworks extension on Linux, but nowadays they're obsolete due to the Steam Runtime migration on YoYo's side.

## ...and basically doing what YoYon't (I'm sorry)

- [kvAberrationFilter](https://github.com/nkrapivin/kvAberrationFilter)

    A port of Keevee's aberration shader as an IDE layer filter, yes, not approved by YYG.

- [bktGlitchFilter](https://github.com/nkrapivin/bktGlitchFilter)

    Same thing except it's a port of odditica's bktGlitch shader.

## Reverse engineering work that's not related to YoYoGames

- [epos.py](https://github.com/nkrapivin/epos.py)

    A Python library to communicate with the EPOS web diary used in Russia, Permskiy krai.
    
- I'd list more but I probably shouldn't... :|

## Making software

- [Undertale Spaghetti Project installer](https://github.com/USPAssets/Installer)

    I made an installer for a fan italian translation of Undertale, called the Undertale Spaghetti Project.
    
    It's written in C#, the UI is written in Avalonia, and compiled with .NET 5 for Windows, Linux and even macOS!

- [JniGen](https://github.com/nkrapivin/JniGen)

    This is a tool to generate glue JNI->C code for native C/C++ Android GameMaker extensions.
    
    Since GameMaker's Android module doesn't allow you to call into C/C++ native libraries directly, you need to go through the awful chain:
    
    GML -> C++ (engine) -> JNI -> Java (engine java code) -> JNI -> C/C++ (your extension)
    
    And JniGen allows to automate this process a little.


See ya~


<!-- +10 points if you read this -->

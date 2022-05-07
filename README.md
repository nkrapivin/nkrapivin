### Hello 👋!

I really don't like emotes so that wave will be the first and the last.

<!-- and I also hate markdown... >:( -->

My name's Nik, or Nikita Krapivin if you prefer boring legal names, I speak English and Russian, my timezone is UTC+05 or MSK+02.

I'm 16 years old and a student at PAT.

# How to reach me

- Discord: nik (octothorpe) 5351
- E-Mail: basically the email I use for my git commits, well, alienoom (the at symbol) yandex (dot) ru
- Twitter: (at) nkrapivindev
- GitHub: you're here!
- VK (Russian only please): (at) nkrapivindev

I'm also present at some Discord servers related to GameMaker research like Underminers and the GameMaker Kitchen.

Oh, right, here's a (somewhat) short list of my activities:

## Making native extensions for GameMaker

- [NekoPresence](https://github.com/nkrapivin/NekoPresence)

    This is an open source wrapper around Discord's rich presence library for GameMaker.
    
    It's used in many games, for example [Mondealy: Day One](https://store.steampowered.com/app/1591570/Mondealy_Day_One/), [Vividerie](https://store.steampowered.com/app/1769200/Vividerie/), [MAKE ME REAL](https://asire.itch.io/make-me-real) or [Wally and the FANTASTIC PREDATORS](https://store.steampowered.com/app/1077450/Wally_and_the_FANTASTIC_PREDATORS/).

- [GMESCAPI](https://github.com/nkrapivin/GMESCAPI)

    This is a fork of the ESCAPI webcam library that adds GameMaker support, so yeah, this is a webcam extension for GameMaker.
    
    Sadly I don't know of any public games that actually use it, maybe because it's kinda spooky to take pictures from the webcam nowadays? Who knows.

- [libmulti](https://github.com/nkrapivin/libmulti)

    This is a library to create and manage multiple windows from GameMaker, very useful for in-game tools like level editors or whatnot.
    
    It's using Direct2D for rendering and accepts GML surfaces as canvases.

## Making GML libraries for GameMaker

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

## Fixing YoYoGames's mistakes

- [Zeus Plugin Loader](https://github.com/ZeusPlugins/ZeusPluginLoader)

    This is a thing to load C# plugins into the GameMaker IDE.
    
    There's not much I can say about it other than it's still not an official feature for whatever reason.

- [nikXfix](https://gist.github.com/nkrapivin/452c1509559cff0945f141910aa098a8)

    A very small C library that "fixes" non-English layouts in the Linux export by unsetting the X11 language bit when the engine tries to read keyboard input.
    
    This is currently used in [Mondealy: Day One](https://store.steampowered.com/app/1591570/Mondealy_Day_One/)

- I also made workarounds for some issues with the new Steamworks extension on Linux, but nowadays they're obsolete due to the Steam Runtime migration on YoYo's side.

## ...and basically doing what YoYon't (I'm sorry)

- [kvAberrationFilter](https://github.com/nkrapivin/kvAberrationFilter)

    A port of Keevee's aberration shader as an IDE layer filter, yes, not approved by YYG.

- [bktGlitchFilter](https://github.com/nkrapivin/bktGlitchFilter)

    Same thing except it's a port of odditica's bktGlitch shader.
    
- [Rouselle](https://github.com/nkrapivin/Rouselle)

    A browser extension to bypass the Opera GX check in the Opera GX (aka WebAssembly) GameMaker export.
    
    No need to install that weird sketchy browser. Use your fav. Firefox or Chrome. <3

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

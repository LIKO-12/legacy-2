# Installation guide

This guide will help you install LIKO-12 on your machine. LIKO-12 is available
ont Windows, Linux, macOS and Android.

You can download LIKo-12 releases on:

* [GitHub](https://github.com/LIKO-12/LIKO-12/releases)
* [Itch.io](https://ramilego4game.itch.io/liko12)

If you are on Android, you get LIKO-12 directly on [Google Play](https://play.google.com/store/apps/details?id=me.ramilego4game.liko12).

## Windows

1. Download the Windows build (`..._Windows.zip`)
2. Unzip the `.zip` file
3. Launch `LIKO-12.exe`

## Linux

There are two different methods to get LIKO-12 on Linux: either using a `.love`
file or using an AppImage. It is recommend to use the first method.

### Using the `.love` file

1. Install LÖVE 11.1 from [http://love2d.org](http://love2d.org)
2. Download the universal `.love` file (`..._Universal.love`)
3. If you want to enable HTTPS support, install the `luasec` package (either
   with your system package manager or [LuaRocks](https://luarocks.org/));
   otherwise you can skip this
4. Execute `love LIKO-12_..._Universal.love`

> If you cannot install `luasec` for any reason, you can install `libcurl` as a
> replacement

### Using the AppImage (only works on 64-bits systems)

!> The AppImage can't open its data folder, and the data folder location is also unknown

1. Download the Linux .AppImage (`..._Linux_x86_64.AppImage`)
2. Make it executablewith `chmod u+x LIKO-12_..._Linux_x86_64.AppImage`
3. If you want to enable HTTPS support, install the `luasec` package (either
   with your system package manager or [LuaRocks](https://luarocks.org/));
   otherwise you can skip this
4. Execute the AppImage with `./LIKO-12_..._Linux_x86_64.AppImage`

> If you cannot install `luasec` for any reason, you can install `libcurl` as a
> replacement

## macOS

?> HTTPS support in LIKO-12 should work out of the box in macOS (using
`libcurl`, which is pre-installed in macOS)

1. Install LÖVE 11.1 from [http://love2d.org](http://love2d.org)
2. Download the universal `.love` file (`..._Universal.love`)
3. Run the universal `.love` file using LÖVE 11.1

> We also provide macOS builds of LIKO-12 (`..._Mac.zip`), but please note that
> those builds are not supported and not guaranteed to work

## Android


It is highly recommended to install LIKO-12 from [Google Play](https://play.google.com/store/apps/details?id=me.ramilego4game.liko12).

As an alternative, we provide an APK (`..._Android.apk`).

Please note that since Google signs LIKO-12 with a different key when downloaded
from Google Play, if you switch between the Google Play release of LIKO-12 and
another release, your data won't be saved (so you will need to make a backup in
this situation).

# What's next

You can start reading [LIKO-12 "Getting Started" guide](/Documentation/Guides/getting_started.md).

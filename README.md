#Ch3at
Download and install NTR Cheat Plugins for your 3ds easily! App based on [Homebr3w](https://github.com/Wolvan/Homebr3w)

##Usage
Simply download the .cia file from the [releases page](https://github.com/no1dead/Ch3at/releases) and install it with your favorite .cia Installer, for example FBI. You can also just scan the QR Code from the releases page as well.

You can also use the .3ds version for a flashcard or the .3dsx version for *hax.

Note: The .3dsx version does not support launching freeShop through it, the option is disabled.

## Nightlies
Nightlies are available at [the official automatic Nightly build page](https://wolvan.github.io/Homebr3w/build/) and build whenever changes get pushed to the `master` branch

## Differences between Builds
There are 2 different builds available, the `.3ds`/`.cia` build and the `.3dsx` NH(2) Build.

`.3ds` for Flashcards and `.cia` to install to Homemenu are identical in functionality and have the full set of features available.

`.3dsx` is slightly limited in its functionality as it is not able to install or launch `.cia`'s from the Homemenu. The functionality is automatically disabled in the `.3dsx` builds.

##Build instructions
The building is made possible through a `make` script, meaning you need to have `make` installed and in your path. If you already use devkitArm then you are good to go

Just run `make` (or `make all`/`make build`) to get your binaries in the build directory

`build 3ds` and `build cia` are also available in case not all binaries need to be built. `built 3dsx` is currently not available due to conflicts with lpp-3ds's networking features on *hax.

You can also use `make clean` to remove all built files.

##Credits
[Rinnegatamante](https://github.com/Rinnegatamante/) - for making [lpp-3ds](https://github.com/Rinnegatamante/lpp-3ds)

[ksanislo](https://github.com/ksanislo) - for making TitleDB.com

[yellows8](https://github.com/yellows8) - for the base of the Icon and Banner

3DSGuy - for converting the Wii HBLauncher's theme to CWAV

[TitleDB.com](https://titledb.com/) - as Database to pull the apps from

[Wolvan](https://github.com/Wolvan/) for making [Homebr3w](https://github.com/Wolvan/homebr3w), and helping me out with this.

The people from the /hbg/ Discord - Beta testing

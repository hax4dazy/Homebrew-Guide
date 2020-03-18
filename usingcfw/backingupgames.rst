Backing Up Games and Playing Them
=================================

Should you backup your games? When it comes to physical copies because the switch uses gamecards, instead of some kind of disc-based media, the chances of damaging them is not as great. However the chances of misplacing or losing a game (especially with the portable nature of the Switch) is much higher. For digital eShop titles we have seen time and time again that digital storefronts do not last forever, and that games you think you own can be removed with no way of getting it back. Keeping a backup of both your physical and digital games offset these risks and could even add some additional conveniences to playing your games on your Switch. With all this being said, the legality of backing up your games differs from place to place, and it's your responsibility to check the laws where you reside.

Getting Started
---------------

First things first, playing backups on your Switch will get your console banned if your Switch is given the chance to communicate back to Nintendo. There are a couple ways to mitigate this:

- Keep your Switch in airplane mode, or just never connect it to a network.
- Use a DNS service like 90DNS, or Pegascape to block all network communications back to Nintendo.

Using either of these methods (as of the time of writing this guide) should prevent your console from being banned, to the best of our knowledge. To get started we will need somethings:

- `Gamecard Installer NX <https://github.com/ITotalJustice/Gamecard-Installer-NX/releases/latest/>`_ to install physical games directly from the gamecard to your Switch.
- `Goldleaf <https://github.com/XorTroll/Goldleaf/releases/latest>`_ to install NSPs on to your Switch via your SD card or over USB.
- `Joonie86's Patches <https://github.com/Joonie86/hekate/releases/latest>`_ are used to patch checks in Horizon to allow backups to be played. If you are interested in just backing up your games, then these aren't required.
- `Lockpick RCM <https://github.com/shchmue/Lockpick_RCM/releases/latest>`_ is used to dump the keys for your console, and titles. These keys are used by nxdumptool to backup eShop titles.
- `nxdumptool <https://github.com/DarkMatterCore/nxdumptool/releases/latest>`_ is used to dump both physical, and digital games. For physical games it can dump them to either an XCI file, or as an NSP file. Currently only NSPs can be used to play backups, unless you are running SX OS.

Backing Up Games
----------------


.. toctree::
   :maxdepth: 2
   :caption: Contents:
   :hidden:

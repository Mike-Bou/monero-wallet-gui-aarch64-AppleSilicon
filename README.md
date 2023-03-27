# monero-wallet-gui-aarch64-AppleSilicon

Monero wallet Gui files, compiled on M1 Macbook Pro, for arm64-apple-darwin22.3.0 kernel, Apple clang version 14.0.0 (clang-1400.0.29.102)
built on Ventura OS, works on Monterey. Target (maybe) macOS 10.12 - 10.13 for better backwards compability.

It is quite easy to build from the original source code at https://github.com/monero-project/monero-gui using command: make release -j4

Built with Qt 5.15.8

v0.18.2.0:

Latest Version 0.18.2.0 in Releases, is also available in .tgz at https://home.mikebouckley.xyz/download/

Install using command line, in Terminal by changing to /Applications folder and sudo tar xzvf ~/Downloads/monero-wallet-gui-0.18.2.0.tgz
it is unsigned for Apple, so otherwise difficult to copy. There may be an initial warning dialog on execution, just Allow it. Or in Finder, right click to open, and confirm any dialogs.

GUI Version 0.18.2.0-release (Qt 5.15.8)
Embedded monero version 0.18.2.0-99be9a044

Note: this version seems to have no control over the location of the 135Gb database created by monerod, default is in your home/.bitmonero/lmdb (which can be sym-linked). The database seems to be activated even in simple mode, but if the location is unavailable, the wallet gui will still work.

v0.18.1.2:

I could not yet create an Apple .dmg of just the monero-wallet-gui.app, and the file i made is nearly 500Mb, of the compiled source, which is too big for github. There is a supporting website, at https://home.mikebouckley.xyz/download/

Where the .dmg, and 2 tar archives, one of the supporting, command line tools may be downloaded from.

The monero-gui.dmg has the monero-wallet.app (and other tools) in build/release/bin/
i found that double clicking on the dmg opened the monero wallet gui.

My Server is usually availiable 24/7. Its solar powered, so occasionally OUT late at night, or for maintainance. On Fiber 100mbs. Certbot / Letsencrypt SSL Certificate. It is a dynamic IP Address, Occasionally the IP Number is changed.  Hosted in Philippines.

The 10Mb. monero-wallet-gui.app is here, and in Releases ( -with a longer file name) in tar.xz format.

This version has better control over the monerod database location, and works normally in simple mode.


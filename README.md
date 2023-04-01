# monero-wallet-gui-aarch64-AppleSilicon

Monero wallet Gui files, compiled on M1 Macbook Pro, for arm64-apple-darwin22.3.0 kernel, Apple clang version 14.0.0 (clang-1400.0.29.102)
built on Ventura OS, works on Monterey. Target (maybe) macOS 10.12 - 10.13 for better backwards compability.

If Qt is configured ok, it is quite easy to build from the original source code at https://github.com/monero-project/monero-gui using command: 'make release -j4'

Built with Qt 5.15.8 from Homebrew.

v0.18.2.0:

Latest Version 0.18.2.0 in Releases, is also available in .tgz at https://home.mikebouckley.xyz/download/

Install using command line, in Terminal by changing to /Applications folder and sudo tar xzvf ~/Downloads/monero-wallet-gui-0.18.2.0.tgz
it is unsigned for Apple, so otherwise difficult to copy. There may be an initial warning dialog on execution, just Allow it. Or in Finder, right click to open, and confirm any dialogs.

Built with 'cmake -D CMAKE_BUILD_TYPE=Release -D ARCH=default -D CMAKE_PREFIX_PATH= /opt/homebrew/Cellar/qt@5/5.15.8_2/clang_64 ..'

GUI Version 0.18.2.0-release (Qt 5.15.8)
Embedded monero version 0.18.2.0-99be9a044

I am still working on it, built Qt 5.15.8 from source, ran 'make deploy' and trying to sign and get Notarised the Application.

v0.18.1.2:

Built with 'make release -j4' (4 Threads). 

I could not yet create an Apple .dmg of just the monero-wallet-gui.app, and the file i made is nearly 500Mb, of the compiled source, which is too big for github. There is a supporting website, at https://home.mikebouckley.xyz/download/

Where the .dmg, and 2 tar archives, one of the supporting, command line tools may be downloaded from.

The monero-gui.dmg has the monero-wallet.app (and other tools) in build/release/bin/
i found that double clicking on the dmg opened the monero wallet gui.

My Server is usually availiable 24/7. Its solar powered, so occasionally OUT late at night, or for maintainance. On Fiber 100mbs. Certbot / Letsencrypt SSL Certificate. It is a dynamic IP Address, Occasionally the IP Number is changed.  Hosted in Philippines.

The 10Mb. monero-wallet-gui.app is here, and in Releases ( -with a longer file name) in tar.xz format.



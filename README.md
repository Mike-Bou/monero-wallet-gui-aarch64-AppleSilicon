# monero-wallet-gui-aarch64-AppleSilicon

V0.18.3.3:

The Monero Org has now released an ARM64 version for MAC OS, also, later, Linux and Windows.

Download from <a href="getmonero.org">getmonero.org</a> or:

<a href="https://github.com/monero-project/monero-gui/releases/tag/v0.18.3.1">github</a>
__________________________________________________________________________________________________________________________________________

Previous Versions:

Monero wallet Gui files, compiled on M1 Macbook Pro, for arm64-apple-darwin22.3.0 kernel, Apple clang version 14.0.0 (clang-1400.0.29.102)
built on Ventura OS 13.4.1, should work on Monterey. 
Target (maybe): macOS 10.12 - 10.13 for better backwards compability. All M1 Macs should be on at least Big Sur 11.7.8 +
The Apple Target is Ventura 13.4

If Qt is configured ok, it is quite easy to build from the original source code at https://github.com/monero-project/monero-gui using command: 'make release -j4'

Built with Qt 5.15.8 from Homebrew.

v0.18.2.2 is the last one i built.

Source Code downloaded from:
git clone --branch master --recursive https://github.com/monero-project/monero-gui.git
or substituting master for version eg v0.18.3.3

Built with 'cmake -D CMAKE_BUILD_TYPE=Release -D ARCH=default -D CMAKE_PREFIX_PATH= /opt/homebrew/Cellar/qt@5/5.15.8_2/clang_64 ..
&& make
&& make deploy'

Codesigned.

Any problems, try installing qt@5 from homebrew: https://brew.sh 'brew install qt@5'

This project is now archive only. I could not build version 0.18.3.1, due to qt problems, which needs patching.
Use the new official version.

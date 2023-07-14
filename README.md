# monero-wallet-gui-aarch64-AppleSilicon

Monero wallet Gui files, compiled on M1 Macbook Pro, for arm64-apple-darwin22.3.0 kernel, Apple clang version 14.0.0 (clang-1400.0.29.102)
built on Ventura OS 14.4.1, should work on Monterey. 
Target (maybe): macOS 10.12 - 10.13 for better backwards compability. All M1 Macs should be on at least 11.7.8
Apple Target: Ventura 13.4

If Qt is configured ok, it is quite easy to build from the original source code at https://github.com/monero-project/monero-gui using command: 'make release -j4'

Built with Qt 5.15.8 from Homebrew.

v0.18.2.2:

Version 0.18.2.2 in Releases, is available at one or both of:
https://home.mikebouckley.xyz:8443/download/
https://www.mikebouckley.net/download/
-with screenshots showing it working.


Source Code downloaded from:
git clone --branch master --recursive https://github.com/monero-project/monero-gui.git
or substituting master for version eg v0.18.2.2

Built with 'cmake -D CMAKE_BUILD_TYPE=Release -D ARCH=default -D CMAKE_PREFIX_PATH= /opt/homebrew/Cellar/qt@5/5.15.8_2/clang_64 ..
&& make
&& make deploy'

Codesigned.

Any problems, try installing qt@5 from homebrew: https://brew.sh 'brew install qt@5'



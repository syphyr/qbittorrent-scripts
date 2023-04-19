# qbittorrent-scripts
Build scripts to package qbittorrent as debian installation files

When using gcc-8, g++-8, and cpp-8 for building qBittorent sources, the following
patch must be applied to qBittorrent's master branch to support the compiler:
git am ../patches/0001-Fix-cpp-8-linking-stdc-fs.patch

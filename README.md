# Installer for llvm-swift

This installer writes the pkg-config file that [llvm-swift](https://github.com/DanielJamesHeywood/llvm-swift) uses to link [LLVM](https://llvm.org) on macOS.

[Homebrew](https://brew.sh) installs LLVM without a pkg-config file, and limitations of [Swift Package Manager](https://docs.swift.org/latest/documentation/packagemanagerdocs/) and [Xcode](https://developer.apple.com/xcode/) make providing one the cleanest way to link it.

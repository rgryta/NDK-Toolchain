# Automated NDK Builder

## Issues
1. Requires Python 2.7 as default to bootstrap (bootstrap process attempts to write binary string to a file opened in non-binary mode)
2. Requires clang to bootstrap - bootstrapping builds Python 3.6, but there's a Segmentation Fault error during the build: https://github.com/pyenv/pyenv/issues/1889#issuecomment-837697366

## Sources
1. Buffer52 - https://github.com/buffer51/android-gfortran
2. LLVM Toolchain Guide - https://android.googlesource.com/toolchain/llvm_android/+/main/BUILD.md 

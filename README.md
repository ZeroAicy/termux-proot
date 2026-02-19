proot
=====
[![Travis build status](https://travis-ci.org/termux/proot.svg?branch=master)](https://travis-ci.org/termux/proot)

This is a copy of [the PRoot project](https://github.com/proot-me/PRoot/) with patches applied to work better under [Termux](https://termux.com).

# 在Termux中构建脱离Termux环境的 Termux Proot
1. pkg install clang
2. pkg install git
3. pkg install libtalloc-static [脱离Termux环境的核心]
4. git clone https://github.com/ZeroAicy/termux-proot
5. cd termux-proot
6. make -C src
## 构建事项
1. 可设置 PROOT_UNBUNDLE_LOADER 环境变量是的 PROOT_LOADER不打包到 proot elf 内。

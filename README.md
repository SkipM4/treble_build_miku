# Miku UI GSI

[English](https://github.com/xiaoleGun/treble_build_miku/blob/snowland/README-EN.md)

## 前言
这是送给所有Miku fans的安卓项目，如果不喜欢它请关闭本页面，但不要攻击任何人，尤其是作者。

## Build
要开始构建Miku UI GSI，您需要熟悉[Git和Repo](https://source.android.com/source/using-repo.html)和[How to build a GSI](https://github.com/phhusson/treble_experimentations/wiki/How-to-build-a-GSI%3F).
- 安装依赖
    ```
    sudo apt-get install bc bison build-essential ccache curl flex g++-multilib gcc-multilib git gnupg gperf imagemagick lib32ncurses5-dev lib32readline-dev lib32z1-dev liblz4-tool libncurses5 libncurses5-dev libsdl1.2-dev libssl-dev libxml2 libxml2-utils lzop pngcrush rsync schedtool squashfs-tools xsltproc zip zlib1g-dev xattr openjdk-11-jdk jq android-sdk-libsparse-utils
    ```
- 新建Miku工作区并进入
    ```
    mkdir miku-treble && cd miku-treble
    ```
- 下载本仓库
    ```
    git clone https://github.com/xiaoleGun/treble_build_miku -b snowland
    ```
- 完成之后运行脚本:
    ```
    bash treble_build_miku/build.sh
    ```

## 感谢
- [Miku-UI](https://github.com/Miku-UI)
- [Project-Mushroom](https://github.com/Project-Mushroom)
- [phhusson](https://github.com/phhusson)
- [AndyCGYan](https://github.com/AndyCGYan)
- [ponces](https://github.com/ponces)
- [Yilliee](https://github.com/Yilliee)

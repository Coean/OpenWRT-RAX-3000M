# Actions-rax3000m-Nand

**English** | [中文](https://p3terx.com/archives/build-openwrt-with-github-actions.html)

# Actions-OpenWrt

[![LICENSE](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square&label=LICENSE)](https://github.com/P3TERX/Actions-OpenWrt/blob/master/LICENSE)
![GitHub Stars](https://img.shields.io/github/stars/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Stars&logo=github)
![GitHub Forks](https://img.shields.io/github/forks/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Forks&logo=github)

Building OpenWrt for CMCC-RAX3000M(SPI-NAND 114M) with GitHub Actions


使用 [hanwckf](https://github.com/hanwckf) 大佬的 [immortalwrt-mt798x](https://github.com/hanwckf/immortalwrt-mt798x) 项目仓库，'openwrt-21.02' 分支源码编译，无线使用 mtwifi 原厂无线驱动，内核版本 5.4.x
项目详情：[immortalwrt-mt798x项目介绍](https://cmi.hanwckf.top/p/immortalwrt-mt798x)

## Tips

- It may take a long time to create a `.config` file and build the OpenWrt firmware. Thus, before create repository to build your own firmware, you may check out if others have already built it which meet your needs by simply [search `Actions-Openwrt` in GitHub](https://github.com/search?q=Actions-openwrt).
- Add some meta info of your built firmware (such as firmware architecture and installed packages) to your repository introduction, this will save others' time.

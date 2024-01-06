# NanoPi-R4S
## 👉使用本固件前，请严格遵守国家互联网使用相关法律规定,不要违反国家法律规定！👈
## 未经许可不得用于任何商用用途。
### 源代码地址
- lede https://github.com/DHDAXCW/lede-rockchip
- Luci https://github.com/DHDAXCW/luci
- packages https://github.com/DHDAXCW/packages

### 固件说明 [releases](https://github.com/vinewx/NanoPi-R4S/releases)
- 自用固件，如需修改请自行fork。

### 固件格式
- **ext4:** 固件文件名中带有 ext4 字样的文件为搭载 ext4 文件系统固件ext4 格式的固件更适合熟悉 Linux 系统的用户使用，在 Linux 下可以比较方便地调整 ext4 分区的大小;
- **squashfs:** 固件文件名中带有 squashfs 字样的文件为搭载 squashfs 文件系统固件而 squashfs 格式的固件适用于“不折腾” 的用户，其优点是可以比较方便地进行系统还原哪怕你一不小心玩坏固件，只要还能进入控制面板或 SSH就可以很方便地进行“系统还原操作”。

### 注：不要用恢复备份，不保证某个插件是否正常运行。建议重新设置贼好！

### 默认编译  

- 修改了scripts/lean.sh管理IP
- 用户名：root 密码：password  管理IP：10.0.0.1
- 下载地址：https://github.com/vinewx/NanoPi-R4S/releases

## 鸣谢

特别感谢以下项目：

Openwrt 官方项目：

<https://github.com/openwrt/openwrt>

Lean 大的 Openwrt 项目：

<https://github.com/coolsnowwolf/lede>

immortalwrt 的 OpenWrt 项目：

<https://github.com/immortalwrt/immortalwrt>

P3TERX 大佬的 Actions-OpenWrt 项目：

<https://github.com/P3TERX/Actions-OpenWrt>

SuLingGG 大佬的 Actions 编译框架 项目：

<https://github.com/SuLingGG/OpenWrt-Rpi>

haiibo 大佬的 Workflows 自动化 项目：

<https://github.com/haiibo/OpenWrt>

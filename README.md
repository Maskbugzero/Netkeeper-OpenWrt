# Actions-OpenWrt
使用 GitHub Actions 云编译 带有 闪讯拨号插件（Netkeeper）的OpenWrt编译项目——适用于x86_64、K2P、K2T、ghl、红米AC2100。
## Tips
SSH 连接到 Actions
- 复制 SSH 连接命令粘贴到终端内执行，或者复制链接在浏览器中打开使用网页终端。（网页终端可能会遇到黑屏的情况，按 Ctrl+C 即可）
- cd openwrt && make menuconfig
- 完成后按Ctrl+D组合键或执行exit命令退出，后续编译工作将自动进行。
## 默认编译
- 用户名：root 密码为空 管理IP：192.168.1.1
## 使用方法
具体请看[wiki](https://github.com/Maskbugzero/lede-Maskbugzero/wiki)
- [Netkeeper插件使用说明](https://github.com/Maskbugzero/Netkeeper-OpenWrt/wiki/Netkeeper%E6%8F%92%E4%BB%B6%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E)
- [自动获取闪讯密码并填写](https://github.com/Maskbugzero/Netkeeper-OpenWrt/wiki/%E8%87%AA%E5%8A%A8%E8%8E%B7%E5%8F%96%E9%97%AA%E8%AE%AF%E5%AF%86%E7%A0%81%E5%B9%B6%E5%A1%AB%E5%86%99)
- [项目说明](https://github.com/Maskbugzero/Netkeeper-OpenWrt/wiki/%E9%A1%B9%E7%9B%AE%E8%AF%B4%E6%98%8E)
## 个人联系方式
- [telegram](https://t.me/Maskbugzero)
## 基于
- [feed-netkeeper](https://github.com/CCnut/feed-netkeeper)
- [SingleNet-Robot](https://github.com/kuretru/SingleNet-Robot)
- [Microsoft Azure](https://azure.microsoft.com)
- [GitHub Actions](https://github.com/features/actions)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)
- [tmate](https://github.com/tmate-io/tmate)
- [mxschmitt/action-tmate](https://github.com/mxschmitt/action-tmate)
- [csexton/debugger-action](https://github.com/csexton/debugger-action)
- [Cowtransfer](https://cowtransfer.com)
- [WeTransfer](https://wetransfer.com/)
- [Mikubill/transfer](https://github.com/Mikubill/transfer)
- [softprops/action-gh-release](https://github.com/softprops/action-gh-release)
- [c-hive/gha-remove-artifacts](https://github.com/c-hive/gha-remove-artifacts)
- [dev-drprasad/delete-older-releases](https://github.com/dev-drprasad/delete-older-releases)

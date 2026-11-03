# reBar

原生 macOS 菜单栏管理工具。

[下载 reBar 1.11.5（Apple Silicon）](https://github.com/BlueOriginAI/reBar/releases/download/v1.11.5/reBar-1.11.5-macOS-arm64.dmg) · [版本说明](https://github.com/BlueOriginAI/reBar/releases/tag/v1.11.5)

## 使用

- 左键点击菜单栏箭头：展开／收起图标。
- 右键点击箭头，选择“显示主窗口”：打开设置。
- 按住 `⌘` 拖动真实菜单栏图标：箭头左侧收起后隐藏，右侧保持显示。
- 全局快捷键、登录启动和自动收起可在设置中调整。
- 有效的本地签名权益缓存用于账户与 Pro 状态展示；云端配置需要账户与 Pro 验证。

## 安装

macOS 13+，Apple Silicon（arm64）。下载已完成 Developer ID 签名与 Apple 公证的 DMG，将 reBar.app 拖入 Applications。

需要比较文件完整性时，使用版本附件中的 SHA256SUMS.txt。Intel 安装包暂未提供。

## 仓库与历史

此公开仓库用于安装包、版本说明与发布元数据。源码位于私有的 BlueOriginAI/reBar-source。

历史 reBar Go / reRoute 标签与安装包保留供旧用户查询；当前原生 reBar 继续使用 1.11.x 版本号。reRoute 的当前公开仓库为 [BlueOriginAI/reRoute](https://github.com/BlueOriginAI/reRoute)。

reBar 基于 [Hidden Bar](https://github.com/dwarvesf/hidden)，第三方组件的版权与许可见 [THIRD_PARTY_NOTICES.txt](THIRD_PARTY_NOTICES.txt)，应用内保留相应声明。

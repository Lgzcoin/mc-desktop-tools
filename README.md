# MC 桌面工具（mc-desktop-tools）

不碰游戏进程的 Windows 小工具，纯 PowerShell / HTML。

## 计划收录
- 模组包体检：扫 mods 里每个 jar 的 fabric.mod.json，报告缺依赖、版本冲突、重复、Java 要求不符
- 存档 / 实例快照：定时打包 bots + 配置 + mods，保留 7 份，一键回滚
- 截图管家：按服务器 / 日期归档，文件名带坐标维度
- 多开性能看板：每个 MC 进程 CPU / 内存 / FPS / 延迟，卡了标红

## 约定
- PowerShell 5.1 兼容，UTF-8 单份 BOM，双击即用，不要 UAC
- 只读文件、只写自己的目录，不动用户配置

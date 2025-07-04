# 编辑日志

仅列出当下季度的编辑日志。其他存档在项目的 [CHANGELOG-ARCHIVE.md](https://docs.bsdcn.org/CHANGELOG-ARCHIVE) 文件中。

## 2025 年第二季度

- 2025.6.21
  - 格式化：第 21.5 节 ArchLinux 兼容层（基于 archlinux-pacman）
  - 为镜像站 <https://docs.bsdcn.org/> 添加了自动序号
- 2025.6.20
  - 第 1.2 节 欢迎来到 FreeBSD：完全重写“为什么选择 FreeBSD”，去除有关 Linux 的描述
- 2025.6.19
  - 调整目录结构
  - 第 19.1 节 PostgreSQL：将 PostgreSQL 更新到 17
  - 第 19.2 节 pgAdmin4 更新到 pgadmin4-9.0
  - 第 23.7 节 ZFS 磁盘加解密合并入 FreeBSD 安装章节
- 2025.6.17
  - 增加一个术语表放在附录
  - 调整目录结构
  - 新增：在 FreeBSD 上安装 VirtualBox
- 2025.6.16
  - 将第 1.2 节 FreeBSD 简史合并入：第 1.2 节 关于 FreeBSD 项目
  - 第 8.2 节 用户和基本账户管理新增：账户类型
  - 将参考书目独立出来放在附录
- 2025.6.15
  - 计划全面重写 FreeBSD 手册
- 2025.6.14
  - 重新引入：[贡献指南与开放任务](CONTRIBUTING.md)
- 2025.6.13
  - 第 1.1 节 操作系统的历程：UNIX、Unix-like、Linux & FreeBSD 重写：什么是 Linux？
  - 第 1.1 节 操作系统的历程：UNIX、Unix-like、Linux & FreeBSD 新增：GNU 与自由软件运动
  - 第 6.6 节 视频播放器新增：附录：直接在 TTY 播放视频（mpv）
- 2025.6.12
  - 第 4.3 节 GNOME：欢迎来到 Gnome 47
- 2025.6.10
  - 第 26.3 节 配置 OpenBSD 重写：doas
  - 第 26.1 节 OpenBSD 概述新增：其他专注于安全的 BSD 系统
  - 第 26.1 节 OpenBSD 概述新增：OpenBSD IPSEC 协议栈 FBI 后门事件
- 2025.6.9
  - 第 26.1 节 OpenBSD 概述新增：机遇与挑战、语录摘选
- 2025.6.8
  - 第 1.1 节 操作系统的历程：UNIX、Unix-like、Linux & FreeBSD 新增：草稿：二十一世纪的 Unix 哲学观
  - 第 1.1 节 操作系统的历程：UNIX、Unix-like、Linux & FreeBSD 增补：UNIX 之船：FreeBSD 是不是 UNIX？
  - 第 4.1 节 显卡驱动（英特尔、AMD）新增：AMD 视频硬解
- 2025.6.7
  - 根据调查问卷恢复一部分文学故事
- 2025.6.6
  - 第 2.3 节 UNIX 基础（新手入门版本）新增：Windows 与 Unix 字符编码的差异
  - 第 2.3 节 UNIX 基础（新手入门版本）新增：Windows 与 Unix 时间设置的差异
  - 第 2.4 节 命令行基础（新手入门版本）：新增“你并不孤单”
- 2025.6.4
  - 第 2.3 节 UNIX 基础（新手入门版本）新增：Windows 与 Unix 换行符/回车之差异，还需要补充编码差异、时区差异等
- 2025.5.30
  - 新增：第 1.7 节 BSD 许可证概览
- 2025.5.23
  - 新增：第 10.3 节 Podman
- 2025.5.17
  - 删除“第 21.2 节 Linux 兼容层——基于 CentOS（FreeBSD Port）”，过时
- 2025.5.16
  - 录制视频 [FreeBSD 14.2 基础安装配置教程](https://www.bilibili.com/video/BV1STExzEEhh)
- 2025.5.12
  - 移除“第 4.18 节 KDE6”中的“基于 Wayland”，可能存在错误
- 2025.5.9
  - 重写：第 22.8 节 Rust/Go 环境的配置
  - 此分支转为社区版本，去除 ykla 个人观点，保留中立内容。该分支转为社区维护，欢迎 PR。
- 2025.5.8
  - 第 2.4 节 命令行基础（新手入门版本）：新增“`vi` 编辑器基本用法”
- 2025.5.6
  - 从“第 2.2 节 FreeBSD 安装图解”拆分出“第 2.1 节 安装前准备（新手入门版本）”
- 2025.5.5
  - 测试“第 22.4 节 C/C++ 环境的配置”
  - 重写“第 4.5 节 Xfce”
  - UNIX 基础（新手入门版本）：新增“大小写敏感”
- 2025.5.2
  - 新增“第 2.3 节 UNIX 基础”
- 2025.4.29
  - 引入 GitHub Action“🔗 检查 Markdown 图片引用”。用以核查图片使用情况
  - 重写“第 5.4 节 五笔输入法”
- 2025.4.28
  - 第 26 章 OpenBSD：更新至 OpenBSD 7.7
  - 将“第 8.2 节 添加用户”合并入“第 8.2 节 用户与组”
  - 重写“第 8.2 节 用户与组”
  - 移除部分来自网络且未经验证的可能不可靠的内容
  - 重写“第 5.4 节 五笔输入法”，注意最后一部分未测试。
  - 重新排版：第 5.1 节 本地化环境变量
  - “第 13.4 节 SSH 配置与相关工具”：删除思考题，删除关于 OpenSSH 版本的描述，因为已经过时。
  - 今天总计清理出了 5 页 A4 纸的篇幅
  - “第 14.1 节 TCP 堆栈”新增“使用 RACK 栈”
- 2025.4.25
  - 重新更名为《FreeBSD 从入门到追忆》
  - 重写“第 6.3 节 打印机”
- 2025.4.24
  - 第 4.2 节 显卡驱动（NVIDIA）：完全重写
- 2025.4.22
  - 《FreeBSD 从入门到跑路》恢复旧名《FreeBSD 艺术科学哲学导论》
- 2025.4.22
  - 第 5.2 节 Fcitx 输入法框架：重新排版
  - 从“第 4.1 节 显卡驱动”拆分出“第 4.1 节 显卡驱动（英特尔、AMD）”、“第 4.2 节 显卡驱动（NVIDIA）”
  - 第 9.3 节 使用 Qjail 管理 Jail：重新排版
  - 由于电子邮件长期被忽视，今日分别致国际信函给“FreeBSD 基金会”（RD664821800CN）和“OpenBSD 基金会”（RD664821795CN），反馈目前的捐款渠道不畅之问题，以及呼吁关注中国大陆地区等
- 2025.4.21
  - “第 5.6 节 QQ（Linux 版）”新增：解决 fcitx 中文输入法在 QQ 中不能使用的问题
  
---

- 2024.8.1-2025.4.20：《FreeBSD 从入门到跑路》第二版完成（TAG 2025.4.20）

---

- 2025.4.20
  - 格式化全书
  - 对全书初版重写达 100%
- 2025.4.19
  - 第 4 章 桌面环境：新增软件解释
  - 对全书删除冗余，重新排版
- 2025.4.18
  - “第 2.2 节 命令行基础（新手入门版本）”新增：关机、重启、`&&`、`||`
- 2025.4.17
  - 重写：第 16.7 节 Samba 服务器中的安装 Samba 部分，其余部分无条件测试
  - 重写：第 16.6 节 rsync 同步服务
- 2025.4.16
  - 格式化：第 14.2 节 WiFi
  - “第 27.4 节 桌面与中文环境常用软件”：重写引入：KDE 4。因为物理机测试成功。
  - 从“第 1.1 节 操作系统的历程：UNIX、Unix-like、Linux & FreeBSD”拆分出“第 1.2 节 FreeBSD 简史”
  - 重写：第 2.6 节 云服务器安装 FreeBSD（基于腾讯云轻量云）
  - 拆分序言
  - 引入 GitHub Action：🔗 从 SUMMARY.md 更新一级标题。用于检查 SUMMARY 标题和对应文件的一级标题的符合情况
- 2025.4.15
  - 格式化：第 5.6 节 QQ（Linux 版）
  - 第 4.20 节 远程桌面：删除剩余的“VNC 与 RPD（XRDP）对比”部分
- 2025.4.14
  - 目前对全书初版已重写 96.57%（按 Commit 数）
  - 格式化“第 11.5 章 MySQL 数据库”
  - 删减占用篇幅较大的无用图片
- 2025.4.13
  - “第 16.5 节 WildFly”测试基本成功，但是注意补丁仍未合并到主线，详见 [Bug 285956 - java/wildfly: service start fail, illegal group name](https://bugs.freebsd.org/bugzilla/show_bug.cgi?id=285956)。
  - 新增“第 24.3 节 配置 DragonFly BSD”
  - 重写“第 24.2 节 安装 DragonFly BSD”
- 2025.4.11
  - 通过段落间距调整，PDF 页数从 1209 到 1084，减少了 10.34% 的页面占用。
- 2025.4.10
  - 测试、改写“第 2.8 节 手动安装双系统（后安装 FreeBSD）”
  - NetBSD 10.1 在 VMware 虚拟机中无论 UEFI 与否，进入 kde 4  都会黑屏。
- 2025.4.9
  - 使用 <https://gist.github.com/ykla/adf011fea43f5f4b91aa6f065ac09da2> 对全书过长（> 30 行）的代码块进行整理。
  - 孤行控制，删除冗余。
  - 从 1238 页到 1209 页，减少了 2.34% 的无效页面。
- 2025.4.8
  - “第 27.2 节 NetBSD 安装图解”更新至 NetBSD 10.1
  - “桌面与中文环境常用软件”更新至 NetBSD 10.1
  - “桌面与中文环境常用软件”新增输入法
  - “桌面与中文环境常用软件”新增中文环境
  - NetBSD KDE 4 UEFI 下测试失败，还是黑屏，报错见 <https://gnats.netbsd.org/57554>
  - “第 16.5 节 Wildfly”测试失败，见 [Bug 285956 - java/wildfly: service start fail, illegal group name](https://bugs.freebsd.org/bugzilla/show_bug.cgi?id=285956)
- 2025.4.7
  - 全译现有所有安装后说明
  - 从 [2024.8-3533 次](https://github.com/FreeBSD-Ask/FreeBSD-Ask/commit/c4d657fb586f91e9f8664ee1181a2711f7350d17) 开始，目前对全书初版已重写 94%（按 Commit 数），下同
  - 删除“第 11.3 节 散热器、风扇、鼓风机”，可能包含错误内容
- 2025.4.6
  - “第 17.8 节 PostgreSQL 与 pgAdmin4”新增“深入 PostgreSQL 服务管理”
  - “第 4.21 节 FreeBSD 桌面发行版”补图
- 2025.4.5
  - 初步重写第 15.4 节 ipfirewall（IPFW）
  - 格式化第 15.2 节 PF
  - 格式化第 15.3 节 IPFilter（IPF）
  - 新增“第 4.21 节 FreeBSD 桌面发行版”
- 2025.4.4
  - 从各个章节拆分出“第 6 章 多媒体与外设”
  - 格式化“第 5.1 节 输入法与环境变量”
  - 格式化“第 21.12 节 Linux 兼容层与 Jail”
  - mihomo（原 Clash），需要重写相关章节，我们需要一个 GUI 界面！
- 2025.4.3
  - 从“第 20.1 节 游戏”拆分出“第 20.6 节 我的世界（Minecraft）”
  - 将“第 20.2 节 音视频播放器与剪辑”拆分为“第 20.2 节 音频播放器”、“第 20.3 节 视频播放器”、“第 20.4 节 音视频剪辑与图像处理”、
  - 测试“第 20.5 节 科研与专业工具”，并新增“Calibre 文档管理（epub、mobi、azw3 等格式）”
  - “第 20.5 节 科研与专业工具”补图
  - “第 20.1 节 游戏”：重写“Renpy 游戏”
- 2025.4.2
  - 测试“第 20.2 节 音视频播放器”：尝试播放电视剧《人民公仆》、尝试播放动漫《败犬女主太多了！》，测试通过
- 2025.4.1
  - <https://mirrors.aliyun.com/freebsd-pkg/> 看起来早就失去同步。还是 2 月我提交 kmod 源以前的内容，故不写入

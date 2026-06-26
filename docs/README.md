# 文档中心

欢迎来到个人文档中心，这里整理了 ZMK 固件和 ESP32 相关项目的使用说明。

---

## ZMK 固件

ZMK 是一个开源、低延迟的无线键盘固件，支持蓝牙 5.0+，适用于各种自定义键盘和翻页器设备。

### 翻页器/键盘设备

| 设备 | 说明 |
| --- | --- |
| 带旋钮翻页器 (RCPen) | 支持旋钮翻页，适合阅读场景 |
| 3键翻页器 (3kbd) | 简洁三键设计 |
| 2键翻页器 (2kbd) | 超轻便两键设计 |
| 5键+1旋钮 (Bento) | 多功能五键加旋钮 |

### 快速上手

- [ZMK 使用帮助](zmk/zmk-help.md) — 基础配置、改键说明、蓝牙操作等完整指南

### 常用链接

| 用途 | 链接 |
| --- | --- |
| 改键配置 | [https://zmk.adamhxx.top/](https://zmk.adamhxx.top/) |
| 备用改键 | [https://zmk.yalishibukede.dpdns.org/](https://zmk.yalishibukede.dpdns.org/) |
| 键值测试 | [https://app.adamhxx.top/test](https://app.adamhxx.top/test) |
| 功耗计算 | [https://zmk.dev/power-profiler](https://zmk.dev/power-profiler) |
| 键码文档 | [https://zmk.dev/docs/keymaps/list-of-keycodes](https://zmk.dev/docs/keymaps/list-of-keycodes) |

---

## ESP32 项目

基于 ESP32 的无线控制设备，通过 WiFi 网络与设备通信，实现远程控制功能。

### 设备列表

| 设备 | 说明 |
| --- | --- |
| Kindle WiFi 翻页器 | 通过 WiFi 远程控制 Kindle 翻页、亮度调节等 |

### 快速上手

- [Kindle WiFi 翻页器使用说明](esp32/kindle-page-turner.md) — 插件安装、WiFi 配网、Web 配置等完整指南

---

## 关于本站

本站使用 [docsify](https://docsify.js.org) 构建，所有文档均为 Markdown 格式，方便阅读和维护。

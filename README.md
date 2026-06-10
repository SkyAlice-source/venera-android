# venera-android — M3 Expressive ✨

> **Android 独立版** | 基于 [venera-app/venera](https://github.com/venera-app/venera)  
> 由 AI 重构并升级为 **Material Design 3 Expressive** 风格

[![flutter](https://img.shields.io/badge/flutter-3.41.4-blue)](https://flutter.dev/)
[![License](https://img.shields.io/github/license/SkyAlice-source/venera-android)](LICENSE)
[![Build](https://github.com/SkyAlice-source/venera-android/actions/workflows/build-android.yml/badge.svg)](https://github.com/SkyAlice-source/venera-android/actions)

一个支持本地和网络漫画的阅读器，**Android 专用**。

## ✨ AI 改造内容

- **移除桌面端** — 清理 Windows/Linux/macOS 平台代码和依赖，仅保留 Android
- **M3 Expressive 色彩系统** — 6 种配色风格可选

| 风格 | 对应 FlexTones | 效果 |
|------|---------------|------|
| **Expressive** 🎯 | `FlexTones.vivid` | 全高饱和度，Secondary/Tertiary 最突出 |
| Tonal Spot | `FlexTones.material` | 标准 Material 3 默认 |
| Vibrant | `FlexTones.vividBackground` | 鲜艳但背景克制（原版风格） |
| Monochromatic | `FlexTones.oneHue` | 单色系极简 |
| Neutral | `FlexTones.soft` | 柔和低饱和 |
| Content | `FlexTones.vividSurfaces` | 内容区色彩丰富 |

- **动态取色** — 设置 → 颜色选「System」，换壁纸即变主题色
- **useMaterial3: true** — 启用 M3 组件圆角/形状系统

## 构建

```bash
flutter build apk --debug
```

## 致谢

原项目：[venera-app/venera](https://github.com/venera-app/venera) — 感谢原作者的出色工作。

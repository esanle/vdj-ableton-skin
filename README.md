# VDJ Skin Default Flat — Ableton Edition

> 一个 Ableton Live 风格的 VirtualDJ 皮肤：扁平无描边 + 珊瑚橙/青色彩体系 + Ableton 原版字体。

![VDJ](https://img.shields.io/badge/VirtualDJ-2020+-blue) ![Style](https://img.shields.io/badge/style-flat-orange) ![Ableton](https://img.shields.io/badge/inspired-Ableton%20Live-ff7657)

## ✨ 特性

- **4 套配色方案**（Color Scheme 菜单切换）：
  - **Default** — Ableton 标准深色（中灰 `#3d3d3d` 底）
  - **Contrast** — 高对比深色（更深底 + 更亮文字）
  - **Dark** — 近黑（`#1a1a1a` 底）
  - **Daylight** — Ableton 浅色主题
- **Ableton 色彩体系**：
  - Deck A/C：珊瑚橙 `#ff7657`（Ableton 标志色）
  - Deck B/D：浅青 `#7ed1d1`
  - Deck 3：浅绿 `#9cd37e` / Deck 4：浅紫 `#b48be1`
- **扁平无描边**：所有按钮、面板、波形、浏览器边框全部去除描边线
- **Ableton 原版字体**：`AbletonSans Small`（从 Ableton Live 12 提取，见 `fonts/`）
- **5 种布局**：Essentials / Pro / Performance / Starter / Vertical

## 📦 安装

1. **安装字体**（必需）：双击 `fonts/` 目录下的 4 个 `.ttf` 文件安装到系统
   - `AbletonSansSmall-Regular.ttf` — 界面主字体
   - `AbletonSansSmall-Bold.ttf` — 数字/强调
   - `AbletonSansSmall-RegularItalic.ttf` — 斜体
   - `AbletonSans-Light.ttf` — 大标题

2. **安装皮肤**：把整个文件夹复制到 VirtualDJ 的 Skins 目录：
   - Windows: `C:\Users\<用户名>\Documents\VirtualDJ\Skins\`
   - macOS: `~/Documents/VirtualDJ/Skins/`

3. 在 VirtualDJ 的 **LAYOUT** 菜单选择 **VDJ Skin Default Flat**

## 🎨 切换配色

LAYOUT → Color Scheme → Default / Contrast / Dark / Daylight

## 📁 目录结构

```
VDJ Skin Default Flat/
├── Essentials.xml        # Essentials 布局
├── Pro.xml               # Pro 布局
├── Performance.xml       # Performance 布局（含 4 deck）
├── Starter.xml           # Starter 布局
├── Vertical.xml          # Vertical 布局
├── gfx-basic.png         # 基础图形精灵
├── gfx-pro.png           # Pro 图形精灵
└── fonts/                # AbletonSans 字体文件
```

## 🛠 自定义

### 修改配色

所有颜色定义在 XML 的 `<group name="colorscheme">` 内：

```xml
<define color="background" value="#3d3d3d"/>   <!-- 主背景 -->
<define color="deckcolor" value="#ff7657" deck="left"/>  <!-- Deck A 色 -->
<define color="deckcolor" value="#7ed1d1" deck="right"/> <!-- Deck B 色 -->
```

### 修改字体

```xml
<font name="Ableton Sans Small"/>
```

## ⚠️ 免责声明

本项目与 Ableton、VirtualDJ / Atomix Productions 均无关联，非官方作品。AbletonSans 字体版权归 Ableton 所有，仅供个人使用。

## 📜 许可

皮肤 XML 基于 VirtualDJ 默认皮肤修改（Atomix Productions 版权），修改部分仅供学习交流。

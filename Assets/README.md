# Assets

Lawlearn 的视觉资源目录。

## Characters

每个角色一个文件夹：

```text
Assets/Characters/<角色>/
├── <角色>_master.png   # 1254 × 1254 主立绘
├── <角色>_color.png    # 160 × 160 彩色头像
└── <角色>_ic.svg       # 2048 × 2048 矢量图标
```

当前包含：

| 角色 | 文件夹 | 备注 |
|---|---|---|
| Cecil | `Characters/Cecil/` | 赛博章鱼男管家 |
| Aetheria | `Characters/Aetheria/` | 赛博章鱼娘女仆 |
| Nox | `Characters/Nox/` | 粉紫色小幽灵 |
| 夏依恩 / Scheien | `Characters/Scheien/` | 獬豸化形的大小姐 |

## Icons

`Icons/` 为 Lawlearn 应用内图标：

- `icon_cecil.png`、`icon_aetheria.png`、`icon_nox.png`、`icon_xiezhi.png`：角色图标
- `icon_seal.png`：印章图标
- `icon_scale.png`：天平图标
- `icon_book.png`：法条/书籍图标

## Brand

- `Brand/AppIcon.icns`：Lawlearn macOS 应用图标。
- `Brand/version-evolution.png`：版本演进视觉，1738 × 316。

## Expressions / Comics

- `Expressions/`：表情包，待补充。
- `Comics/`：四格漫画，待补充。

## 来源

当前文件复制自 `Lawlearn_Mac`：

- `assets/char_masters/` → `Assets/Characters/*/*_master.png`
- `Sources/Lawlearn/Resources/pro_chars/` → `Assets/Characters/*/*_color.png`、`*_ic.svg`
- `Sources/Lawlearn/Resources/icons/` → `Assets/Icons/`
- `Sources/Lawlearn/Resources/AppIcon.icns` → `Assets/Brand/AppIcon.icns`
- `assets/version-evolution.png` → `Assets/Brand/version-evolution.png`

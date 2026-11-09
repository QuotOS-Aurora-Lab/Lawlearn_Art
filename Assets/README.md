# Assets

Lawlearn 的视觉资源目录。

## Characters

每个角色一个文件夹：

```text
Assets/Characters/<角色>/
├── <角色>_master.png   # 1254 × 1254 主立绘
├── <角色>_color.png    # 160 × 160 彩色头像
├── <角色>_ic.svg       # 2048 × 2048 矢量图标
├── <角色>_fullbody.png # 3:4 全身立绘（可选）
└── <角色>_chibi.png    # 3:4 Q 版全身立绘（可选）
```

当前包含：

| 角色 | 文件夹 | 备注 |
|---|---|---|
| 谢辞希 / Cecil | `Characters/Cecil/` | 英伦毒舌管家 |
| 伊诗雅 / Aetheria | `Characters/Aetheria/` | 傲娇章鱼女仆 |
| 罗亘斯 / Nox | `Characters/Nox/` | 无性别数据幽灵 |
| 夏依恩 / Scheien | `Characters/Scheien/` | 獬豸化形的大小姐；含人形 Q 版与设定图 |
| 夏珩 / Scheng | `Characters/Scheng/` | 初代法理獬豸与雪原狼王的后裔；兽形设定图 |
| 作者 / 开发者 | `Characters/Author/` | 苦逼开发者；非五位法理神明之一 |

## Icons

`Icons/` 为 Lawlearn 应用内图标：

- `icon_cecil.png`、`icon_aetheria.png`、`icon_nox.png`、`icon_xiezhi.png`：角色图标
- `icon_seal.png`：印章图标
- `icon_scale.png`：天平图标
- `icon_book.png`：法条/书籍图标

## Brand

- `Brand/AppIcon.icns`：Lawlearn macOS 应用图标。
- `Brand/version-evolution.png`：版本演进视觉，1738 × 316。
- `Brand/Lawlearn_Ad.mp4`：Lawlearn 广告片。

## Expressions / Comics

- `Expressions/Scheng/Moe/`：10 张夏珩兽形 Q 版表情。
- `Comics/挂饰误会/zh.png`、`ja.png`：夏珩与夏依恩的四格漫画《挂饰误会》中文版/日文版（2026-11-07）。
- `Comics/法律学习与短视频风波/zh.png`、`ja.png`、`de.png`：作者、夏珩与伊诗雅的四格漫画《法律学习与短视频风波》中文版/日文版/德语版（2026-11-08）。
- `Comics/降温的好处/zh.png`：作者、夏珩与伊诗雅的四格漫画《降温的好处》中文版（2026-11-09）。
- `Comics/劳逸结合/zh.png`：作者、夏珩与伊诗雅的四格漫画《劳逸结合》中文版（2026-11-09）。
- `Comics/忘带伞/zh.png`：作者、夏珩与伊诗雅的四格漫画《忘带伞》中文版（2026-11-10）。

## 来源

当前文件复制自 `Lawlearn_Mac`：

- `assets/char_masters/` → `Assets/Characters/*/*_master.png`
- `Sources/Lawlearn/Resources/pro_chars/` → `Assets/Characters/*/*_color.png`、`*_ic.svg`
- `Sources/Lawlearn/Resources/icons/` → `Assets/Icons/`
- `Sources/Lawlearn/Resources/AppIcon.icns` → `Assets/Brand/AppIcon.icns`
- `assets/version-evolution.png` → `Assets/Brand/version-evolution.png`

追加素材来自本次提供的 `未命名文件夹 2`：

- `夏依恩_Moe` / `夏依恩_Ori` → `Assets/Characters/Scheien/Humanoid/`
- `夏桁_Moe` / `夏桁_Ori` → `Assets/Characters/Scheng/Ori/`、`Assets/Expressions/Scheng/Moe/`
- `Comics` → `Assets/Comics/挂饰误会/`
- `Scheien_avatar.PNG` → `Assets/Characters/Scheien/Scheien_avatar.png`
- `Lawlearn_Ad.MP4` → `Assets/Brand/Lawlearn_Ad.mp4`

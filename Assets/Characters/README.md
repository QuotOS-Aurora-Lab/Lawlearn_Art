# 角色素材

每个角色一个目录，统一放基础三类文件，并可按需追加全身立绘与 Q 版立绘：

- `*_master.png`：1254 × 1254 主立绘，适合展示、裁切和二次排版。
- `*_color.png`：160 × 160 彩色头像，适合列表、卡片和社交平台头像。
- `*_ic.svg`：2048 × 2048 矢量图标，适合界面图标与印刷。
- `*_fullbody.png`：1024 × 1536 全身立绘，白底，适合角色页、海报和二次排版。
- `*_chibi.png`：约 3:4 的 Q 版全身立绘，白底，适合表情、角色页和轻量传播。

当前角色：谢辞希（Cecil）、伊诗雅（Aetheria）、罗亘斯（Nox）、夏依恩（Scheien）、夏珩（Scheng）。

## 作者 / 开发者（元角色）

作者不是五位法理神明之一，也不在离线誓约的签署者名单里；他是把第七码头写进硬盘的人。

```text
Author/
└── Author_fullbody.png      # 1086 × 1448 作者形象（苦逼开发者）
```

## 伊诗雅 / Aetheria

```text
Aetheria/
├── Aetheria_master.png
├── Aetheria_color.png
├── Aetheria_ic.svg
├── Aetheria_fullbody.png    # 1024 × 1536 全身立绘
├── Aetheria_chibi.png       # 1087 × 1447 Q 版全身立绘
```

## 谢辞希 / Cecil

```text
Cecil/
├── Cecil_master.png
├── Cecil_color.png
├── Cecil_ic.svg
├── Cecil_fullbody.png       # 1024 × 1536 全身立绘
├── Cecil_chibi.png          # 1086 × 1448 Q 版全身立绘
```

## 夏依恩 / Scheien

```text
Scheien/
├── Scheien_master.png
├── Scheien_color.png
├── Scheien_ic.svg
├── Scheien_avatar.png        # 1254 × 1254 头像大图
├── Humanoid/
│   ├── Moe/                  # 2 张 Q 版人形
│   └── Ori/                  # 8 张人形设定图
└── README.md
```

## 夏珩 / Scheng

```text
Scheng/
├── Scheng_avatar.png        # 1254 × 1254 头像大图（取自 Ori/scheng_ori_01.png）
├── Scheng_color.png         # 160 × 160 彩色头像
├── Ori/                      # 6 张兽形设定图（原始文件夹名：夏桁_Ori）
└── README.md
```

夏珩的 10 张 Q 版兽形表情在 [`Assets/Expressions/Scheng/Moe/`](../Expressions/Scheng/Moe/)。

新增角色时，先在本目录建同名文件夹，再在 `../../Characters/` 补角色档案。

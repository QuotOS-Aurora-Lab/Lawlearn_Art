# 角色素材

每个角色一个目录，统一放基础三类文件：

- `*_master.png`：1254 × 1254 主立绘，适合展示、裁切和二次排版。
- `*_color.png`：160 × 160 彩色头像，适合列表、卡片和社交平台头像。
- `*_ic.svg`：2048 × 2048 矢量图标，适合界面图标与印刷。

当前角色：Cecil、Aetheria、Nox、夏依恩（Scheien）、夏珩（Scheng）。

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
├── Ori/                      # 6 张兽形设定图（原始文件夹名：夏桁_Ori）
└── README.md
```

夏珩的 10 张 Q 版兽形表情在 [`Assets/Expressions/Scheng/Moe/`](../Expressions/Scheng/Moe/)。

新增角色时，先在本目录建同名文件夹，再在 `../../Characters/` 补角色档案。

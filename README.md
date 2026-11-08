# Lawlearn Art

Lawlearn 的**艺术资源、角色档案与世界观设定**仓库。

这里集中存放与 Lawlearn 相关的角色立绘、头像、图标、品牌视觉，以及角色性格与说话方式的设定，方便后续补充、整理和对外展示。

> 当前内容最初整理自 [`QuotOS-Aurora-Lab/Lawlearn_Mac`](https://github.com/QuotOS-Aurora-Lab/Lawlearn_Mac)（commit `ef61355`），后续会继续补充世界观、表情包、四格漫画等内容。

## 目录

```text
.
├── Characters/          # 角色档案：性格、语气、角色提示词与头像索引
├── Worldbuilding/       # 世界观设定：神话、组织、时间线、术语
├── Assets/
│   ├── Characters/      # 角色立绘、头像、图标
│   ├── Icons/           # Lawlearn 应用内图标
│   ├── Brand/           # 品牌与版本视觉
│   ├── Expressions/     # 表情包（待补充）
│   └── Comics/          # 四格漫画（待补充）
└── LICENSE
```

## 角色一览

| 角色 | 定位 | 档案 |
|---|---|---|
| Cecil | 赛博章鱼男管家，理性、克制、护短 | [Characters/Cecil.md](Characters/Cecil.md) |
| Aetheria | 赛博章鱼娘女仆，傲娇但靠谱 | [Characters/Aetheria.md](Characters/Aetheria.md) |
| Nox | 粉紫色小幽灵吉祥物，呆萌但关键时刻很聪明 | [Characters/Nox.md](Characters/Nox.md) |
| 夏依恩 / Scheien | 獬豸化形的大小姐，傲娇毒舌、讲究格式 | [Characters/Scheien.md](Characters/Scheien.md) |

## 资源说明

- `Assets/Characters/<角色>/` 内包含：
  - `*_master.png`：1254 × 1254 角色主立绘
  - `*_color.png`：160 × 160 彩色头像
  - `*_ic.svg`：2048 × 2048 矢量图标
- `Characters/aether_presets.json` 是角色行为设定的原始数据，包含 system prompt、称呼、口头禅与角色互动内容。
- `Assets/Icons/` 为 Lawlearn 应用内使用的法务与角色图标。

## 补充约定

- 新增角色时，在 `Characters/` 下新增角色档案，并在 `Assets/Characters/<角色>/` 放对应素材。
- 新增表情包放 `Assets/Expressions/`，四格漫画放 `Assets/Comics/`。
- 世界观、神话体系、组织与时间线统一放 `Worldbuilding/`。

## License

本仓库内容默认保留所有权利，具体使用范围见 [LICENSE](LICENSE)。如需采用其他授权方式，可后续替换。

# 角色档案

本目录存放 Lawlearn / QuotOS Aether 的角色设定。

- [`aether_presets.json`](aether_presets.json)：角色行为设定的原始 JSON，包含 system prompt、称呼、口头禅、角色互动与离线/日常语料。
- 每个角色一份 Markdown 档案，概述定位、语气与素材索引；完整行为规则以 JSON 为准。

## 角色索引

| 角色 | 英文/内部 id | 定位 | 档案 |
|---|---|---|---|
| Cecil | `cecil` | 赛博章鱼男管家 | [Cecil.md](Cecil.md) |
| Aetheria | `aetheria` | 赛博章鱼娘女仆 | [Aetheria.md](Aetheria.md) |
| Nox | `nox` | 粉紫色小幽灵吉祥物 | [Nox.md](Nox.md) |
| 夏依恩 / Scheien | `scheien` | 獬豸化形的大小姐 | [Scheien.md](Scheien.md) |
| 夏珩 / Scheng | —（世界观角色） | 初代法理獬豸与雪原狼王的后裔 | [Scheng.md](Scheng.md) |

> 夏依恩的人形素材在 `Assets/Characters/Scheien/`；兽形素材按设定正名归入 `Assets/Characters/Scheng/` 与 `Assets/Expressions/Scheng/Moe/`（原始文件夹名分别为 `夏桁_Ori`、`夏桁_Moe`）。

## 设定字段

`aether_presets.json` 中每个角色包含：

- `system`：角色行为与语气规则
- `greeting`：开场白
- `comfort`：安慰语料
- `identity`：身份质疑时的回应
- `profanity`：脏话/攻击性输入时的回应
- `rival`：与其他角色的互撕语料
- `daily`：日常对话语料
- `offline`：离线模式语料

新增或修改角色时，优先修改 JSON，再同步 Markdown 档案。

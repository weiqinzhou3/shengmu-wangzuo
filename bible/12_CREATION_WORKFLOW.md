# 十二、后续章节创作流程

## 1. 固定协作关系

### 用户：读者与方向裁决者

- 阅读正文
- 提供真实观后感
- 决定重大方向和人物命运
- 不承担设定检索工作

### ChatGPT：作者

- 负责大纲、正文、人物、对白、节奏和修订
- 将读者意见转为剧情方案
- 同步更新全部设定与状态文件
- 处理 Codex 审查意见

### Codex：审查者

- 读取仓库全部正文和设定
- 发现设定、时间、资源、动机和知识漏洞
- 输出带文件和章节证据的问题报告
- 检查新内容是否完成登记
- 默认不直接改写文学正文

## 2. 每个章节的标准流程

1. 作者读取小说圣经、当前分卷大纲和最近记忆包。
2. 作者读取人物、城市、国家、事件、兵种、宝物、地图和死亡状态。
3. 作者制定单章目标和主要视角。
4. 作者编写正文。
5. 作者更新人物、关系、城市资源、事件、兵种、宝物、地点、背景、势力动机、伏笔与知识矩阵。
6. Codex运行一致性审查。
7. 作者根据审查结果修订或说明保留理由。
8. 用户以读者视角评价是否进入下一章。

## 3. 正文与作者侧文件分离

公开正文不出现：

- 状态表
- 精确游戏面板
- 资源统计报表
- 伏笔编号
- 作者侧现实国家映射

## 4. Git分支与提交

- `main`：确认后的设定与正文
- `agent/<topic>`：每次设定或章节工作分支
- 每次正文提交同时包含相关状态更新
- Codex审查记录单独提交或与修订提交关联

提交示例：

```text
chapter: add vol01 ch003 and update story state
review: add codex findings for vol01 ch003
fix: resolve causality and resource findings in ch003
canon: add sun-country factions and nation aliases
```

## 5. 新内容登记矩阵

| 新内容 | 必须更新 |
|---|---|
| 人物 | `15_CHARACTER_BIBLE.md`、`state/CHARACTER_STATE.md` |
| 爱情/关系 | `state/RELATIONSHIP_MATRIX.md` |
| 事件 | `state/EVENT_LEDGER.md` |
| 背景历史 | `state/BACKGROUND_LORE.md` |
| 兵种 | `state/UNIT_BESTIARY.md` |
| 宝物 | `16_ARTIFACT_SYSTEM.md`、`state/ARTIFACT_LEDGER.md` |
| 地点与路线 | `17_WORLD_MAP.md`、`state/MAP_STATE.md` |
| 国家或派系 | `14_NATION_ALIASES.md`、`18_FACTION_DOSSIERS.md`、`state/NATION_STATE.md`、`state/FACTION_STATE.md` |
| 死亡与不可逆事件 | `state/DEATH_LEDGER.md` |
| 新知识 | `state/KNOWLEDGE_MATRIX.md` |

任何一项遗漏，都由 Codex 标记 `[REGISTRY]`。

## 6. 在线 GitHub 工作流

正式仓库：`weiqinzhou3/shengmu-wangzuo`。

1. 从 `main` 创建 `agent/<topic>` 分支。
2. 作者在同一分支编写正文与相关设定更新。
3. 新人物、事件、兵种、宝物、地点、国家动机分别更新对应账本。
4. Codex依据 `tools/CODEX_REVIEW_PROTOCOL.md` 审查。
5. 作者处理问题并提交修订。
6. 创建 Pull Request，确认后合并 `main`。
7. `main` 只保存已确认的正式事实。

不得仅在聊天中确认重大设定而不回写仓库。

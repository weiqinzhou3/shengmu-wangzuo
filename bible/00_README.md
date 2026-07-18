# 《圣墓王座》小说圣经

- 版本：V1.2-draft
- 状态：核心设定已锁定，第一卷卷级大纲V0.2复审中
- 暂定书名：《圣墓王座》
- 核心城市：丧钟城
- 类型：异界领主、英雄文明、种田建设、国家开拓、多种族群像、全面战争
- 目标读者：中文网络小说读者
- 预计规模：长篇连载，不预设固定章数；十卷代表十个时代，可拆分上下卷

## 每次创作前的必读文件

1. `01_CORE_THEME.md`
2. `02_WORLD_AND_COGNITION.md`
3. `03_POWER_MAGIC_HERO.md`
4. `04_CITY_RESOURCE_POPULATION.md`
5. `05_FACTIONS_NATIONS_WAR.md`
6. `06_CHARACTERS_AND_PERSONHOOD.md`
7. `07_EIGHTH_TIER_AND_RESURRECTION.md`
8. `08_MASTER_OUTLINE.md`
9. `09_STORY_ENGINE.md`
10. `10_CONTINUITY_LEDGER.md`
11. `11_CANON_LOCK.md`
12. `13_COLLABORATION_AND_STYLE.md`
13. `14_NATION_ALIASES.md`
14. `15_CHARACTER_BIBLE.md`
15. `16_ARTIFACT_SYSTEM.md`
16. `17_WORLD_MAP.md`
17. `18_FACTION_DOSSIERS.md`
18. `19_UNDEAD_NEEDS_AND_CIVIC_RECIPROCITY.md`

写第一卷时还必须读取：

- `outline/VOL01_MASTER_OUTLINE.md`
- `state/CITY_STATE.md`
- `state/EVENT_LEDGER.md`
- `state/MAP_STATE.md`
- `state/ARTIFACT_LEDGER.md`
- `state/FACTION_STATE.md`
- `state/CHARACTER_STATE.md`
- `state/RELATIONSHIP_MATRIX.md`
- `state/REVIEW_LOG.md`

## 设定优先级

发生冲突时按以下顺序处理：

1. `11_CANON_LOCK.md` 中的硬规则
2. 已经发布的正文事实
3. 本小说圣经中的正式设定
4. 已通过读者与当时Reviewer复审的分卷大纲
5. 单章计划
6. 临时灵感

不得为了制造爽点，临时破坏死亡、资源、人口、宝物持有链、地理或八阶唯一性。

## 版本管理

每次重大修改记录：

- 修改日期
- 修改文件
- 修改原因
- 影响章节
- 是否需要回查已发布正文
- 对应Review ID与处理提交

GitHub `main` 保存已确认事实；大纲与正文先在独立主题分支接受用户指定Reviewer审查，再通过Pull Request合并。

## 新设定回写规则

正文首次出现下列内容时，必须在同一提交或同一PR更新：

- 新人物：`15_CHARACTER_BIBLE.md` 与 `state/CHARACTER_STATE.md`
- 新事件：`state/EVENT_LEDGER.md`
- 新背景故事或历史：`state/BACKGROUND_LORE.md`
- 新兵种、亡灵需求或兵种例外：`state/UNIT_BESTIARY.md`
- 新国家、派系或外交关系：`14_NATION_ALIASES.md`、`18_FACTION_DOSSIERS.md`、`state/NATION_STATE.md`、`state/FACTION_STATE.md`
- 新宝物或宝物状态变化：`16_ARTIFACT_SYSTEM.md` 与 `state/ARTIFACT_LEDGER.md`
- 新地点、路线或地图知识：`17_WORLD_MAP.md` 与 `state/MAP_STATE.md`
- 新爱情、友情、债务或关系变化：`state/RELATIONSHIP_MATRIX.md`
- 新死亡或不可逆事件：`state/DEATH_LEDGER.md`
- 新的角色知识或错误认知：`state/KNOWLEDGE_MATRIX.md`

不得只写入正文而不更新设定账本。

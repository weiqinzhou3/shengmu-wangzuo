# 《圣墓王座》长篇小说项目

本仓库是《圣墓王座》的**唯一设定、正文与连续性事实来源**。聊天记录和离线文件不作为最终依据。

## 协作角色

- 用户：读者与方向裁决者
- ChatGPT：作者，负责编写、修订和设定回写
- Codex：证据型Reviewer，负责发现漏洞与连续性问题

## 目录

```text
bible/      小说圣经、风格、人物、地图、宝物、国家联盟和硬规则
outline/    分卷、剧情单元和章节大纲
chapters/   正文
state/      人物、事件、兵种、宝物、地图、国家、关系、知识和死亡账本
summaries/  章节摘要与记忆包
tools/      Codex审查协议和一致性工具
```

## 核心写作原则

- 群像人物拥有独立意志、生活、关系和政治判断
- 事件遵循动机、信息、资源、地理、法权和历史因果
- 公开正文中的现实国家使用小说代称
- 风格为“史诗骨架、人物驱动、严肃底色、克制幽默”
- 爱情线自然生长，不写后宫，不取消人物独立性
- 宝物有实体、等级、归属、持有者、代价和维护要求
- 不同种族不需要相同资源；城市认同来自人格保护、互惠服务、共同安全和可执行契约
- 世界地图采用读者熟悉的全球拓扑，但国家边界与文明历史原创
- 新人物、事件、背景、兵种、宝物、地点、国家或联盟动机必须在同一Pull Request同步登记
- 正文与状态更新必须同一提交或同一PR完成

## 当前核心文件

- `bible/11_CANON_LOCK.md`：最高优先级硬规则
- `bible/13_COLLABORATION_AND_STYLE.md`：协作与文风
- `bible/15_CHARACTER_BIBLE.md`：人物圣经
- `bible/16_ARTIFACT_SYSTEM.md`：宝物体系与卷一宝物持有链
- `bible/17_WORLD_MAP.md`：世界地图
- `bible/18_FACTION_DOSSIERS.md`：国家与联盟背景动机
- `bible/19_UNDEAD_NEEDS_AND_CIVIC_RECIPROCITY.md`：亡灵需求与城市互惠
- `outline/VOL01_MASTER_OUTLINE.md`：第一卷卷级大纲
- `state/ARTIFACT_LEDGER.md`：宝物持有者与状态
- `state/FACTION_STATE.md`：势力动态
- `state/MAP_STATE.md`：地点与路线
- `state/REVIEW_LOG.md`：Codex审查与作者处理

## 当前工作状态

- 工作分支：`agent/volume-01-outline`
- Draft PR：`#2`
- 卷一大纲版本：V0.2
- 正确Codex审查：`REV-20260716-002`，来自PR #4
- 当前阶段：作者修订后等待Codex复审，不合并`main`

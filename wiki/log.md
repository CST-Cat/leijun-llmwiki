# 维护记录

这里只记录实际完成的动作、阅读范围、理解变化、未解决问题和验收依据。Agent 自查与人工 review 分开记录，不以计划代替结果。

## 2026-09-22 · P0 原则冻结

覆盖原 AGENTS.md，新增 README；只改维护纪律与项目说明，没有 ingest。提交：`70c9e86`。

规则清晰度自查：raw 由人工维护，Agent 只读；新建需有独立长期价值且无法由旧页承载；新资料先读旧页并改写；查询从 index 出发；精确事实与冲突回 raw；不同说法保留归因和时间；每次事务回读、检查、维护 index/log、查看 diff、人工 review 后单独 commit。七个问题均在 AGENTS 有明确答案。此项是 Agent 自查，没有声称发生独立 Agent 或人工验收。

## 2026-09-22 · P1 最小目录

将 `data/raw/` 原样迁移为 `raw/`，移除空占位文件 `data/.gitkeep`，建立本文件与 index。原始文件共 62 份：books 8、interviews 23、speeches 15、wechat 16；迁移逐文件比对 Git blob 与内容，保持不变。

Exit Gate：README、AGENTS、raw、index、log 均存在；Wiki 中只有 index/log，真实知识页为 0；未建立主题目录、schema 或工具。结构与知识改动分离。P2 尚未验收，P3 未开始。

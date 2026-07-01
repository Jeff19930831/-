# 采购数据处理（大项目）— 计划

> 父项目计划只管**归口与新子项目立项**；具体开发计划在各子项目自己的 plan/handoff 里。

## Active

- [ ] 季度图表总结：等待业务方 Q2 数据 → 到位后接入并出图（阻塞在数据侧）
- [ ] 维护子项目清单与根 SSOT 的 `subprojects` 一致

## Next

- [ ] 视需求新增采购子项目（候选方向：数据清洗、格式转换、报表导出）
- [ ] 各子项目统一迁入 / 新建于 `D:\workspace`

## 立项规范（新子项目）

1. 在 `D:\workspace\<英文-kebab-name>` 建代码仓库
2. 建知识库文档 `Jeff1993/<name>/`（HANDOFF/PROGRESS/README）
3. 根 `Jeff1993/.project-status.yaml`：新增条目并加 `parent: 采购数据处理`
4. 本项目 `handoff.md` 子项目清单 + 根 SSOT `subprojects` 同步登记

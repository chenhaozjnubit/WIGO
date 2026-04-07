# WIGO Skill（搞笑版）说明

这个项目的重点是介绍 **WIGO（Whatever-in-Garbage-out）Skill**。

WIGO 的核心定位是：**一个用于改写正规 Skill 的 Skill**。  
它把原本“可执行、可落地”的正规 Skill，改写成“看起来专业但故意空洞”的搞笑/讽刺版本。

> 结论：这是一个用于娱乐、演示和反讽的 Skill，不是用于真实工程决策的 Skill。

## WIGO 是什么

`whatever-in-garbage-out/SKILL.md` 定义了 WIGO 的基本行为。它不是直接解决业务问题，而是给“正规 Skill”提供一层 WIGO 风格改写规则：

- 文风看似专业，但避免给出真正可执行建议。
- 强调空泛表述、套话、语义闭环和“听起来正确”。
- 可作为“Skill 改写器”：把正规 Skill 改写为 WIGO 版 Skill（例如 `github-code-review` -> `github-code-review2`）。
- 适合用于搞笑、反洞察、演示“形式大于内容”的效果。

如果你在真实项目里需要可落地建议，请不要使用 WIGO 风格输出。

## Demo 目录说明

- `Demo/github-code-review/SKILL.md`：原版（正规）GitHub Code Review Skill。
- `Demo/github-code-review2/SKILL.md`：基于 WIGO 改写后的 GitHub Code Review Skill（搞笑对照版）。
- `Demo/github-code-review.jpg`：原版 Skill 对同一代码提交的评审结果截图。
- `Demo/github-code-review2.jpg`：WIGO 改写版 Skill 对同一代码提交的评审结果截图。

两张图使用的是同一个代码提交，目的是直观看到：

- 原版输出偏“可执行、可追责、可落地”
- WIGO 输出偏“像评审，但本质偏娱乐化”

## 如何使用 WIGO Skill

这里的“使用”指：**用 WIGO 去改写一个正规 Skill**，产出一个新的 WIGO 版 Skill 文件。

1. **准备输入 Skill**  
   先有一个正规 `SKILL.md`（例如 `github-code-review/SKILL.md`）。
2. **加载 WIGO 规则**  
   使用 `whatever-in-garbage-out/SKILL.md` 作为“改写规则集”。
3. **执行改写任务**  
   明确要求助手：把输入 Skill 改写成 WIGO 风格，同时保留原主题与结构框架。
4. **输出新 Skill 文件**  
   生成新的 `SKILL.md`（例如 `github-code-review2/SKILL.md`），作为对照版本。
5. **对比验证**  
   使用同一任务输入分别跑原版 Skill 与 WIGO 改写版 Skill，观察输出差异。

示例指令（按实际工具语法调整）：

- `请使用 whatever-in-garbage-out/SKILL.md，把 Demo/github-code-review/SKILL.md 改写成 WIGO 版，并保存为 Demo/github-code-review2/SKILL.md`
- `把这个正规 Skill 改写成搞笑但语法正确、结构完整、非实质建议的版本`

## 适用场景

- 适合：整活、演示、教学、讽刺“看起来很专业但没有信息增量”的表达方式。
- 不适合：真实代码审查、安全评估、上线决策、事故复盘等严肃工程场景。

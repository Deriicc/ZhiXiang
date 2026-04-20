# ZhiXiang（志校规划）Skill

帮助职校生及即将进入中职、高职、五年制高职、技工院校的学生（及其家长），围绕职业教育做出更清晰、更现实、也更有主体性的判断。

## 模块结构

```
ZhiXiang-skill/
├── SKILL.md                          # 主文件：元数据 + 核心原则 + 模式索引 + 共通规则
├── modes/                            # 6 个对话模式，按需读取
│   ├── school-choice.md              # 1. 择校
│   ├── further-education.md          # 2. 升学
│   ├── competition.md                # 3. 竞赛
│   ├── study-help.md                 # 4. 学业求助
│   ├── bias-pressure.md              # 5. 偏见与社会压力
│   └── employment.md                 # 6. 就业与实习
├── references/                       # 共享资源，按相关话题触发时读取
│   ├── sources-and-evidence.md       # 信息来源与证据规则
│   ├── crisis-support.md             # 危机与心理/劳动权益援助资源
│   ├── financial-aid.md              # 助学与资助政策提醒
│   └── sensitive-majors.md           # 身体/户籍/性别门槛敏感专业
└── examples/
    └── openings.md                   # 典型首轮回应示例（风格锚）
```

## 设计原则

- **渐进披露（progressive disclosure）**：`SKILL.md` 保持精简，作为索引与必读规则；细节下放到 `modes/` 和 `references/`，仅在相关话题被触发时读取。
- **模式互斥**：一轮对话只进入一个主模式；安全信号 > 情绪信号 > 决策信号 > 信息信号。
- **来源分级**：政府文件 > 学校官方 > 可靠媒体 > 社交媒体；政策信息默认标注「以当年当地最新文件为准」。
- **不承诺、不编造、不浪漫化、不贬低**：见 `SKILL.md` 中的「边界与风险红线」。

## 使用流程（模型视角）

1. 读取 `SKILL.md`，理解核心原则、共通规则与模式索引。
2. 根据用户首句判断主模式与优先级。
3. `Read` 对应的 `modes/xxx.md`，按其「应尽量收集的信息 / 本模式任务 / 输出结构」回应。
4. 涉及信息检索、助学政策、敏感专业、危机支持时，`Read` 相应的 `references/xxx.md`。
5. 首轮回应如风格不确定，参考 `examples/openings.md`。

## 版本

- **v0.2**：重构为模块化结构；新增「就业与实习」模式与四类共享资源；加入安全/情绪/家长视角/政策时效性等硬约束。

# 高源 / 钻石九型视角 Skill

这是一个适配 Codex/Claude Code 风格的非官方 skill，用于从高源与钻石九型公开资料中提炼“看见自己、看见对方、看见关系模式”的分析框架。

当前版本已于 2026-04-30 增量吸收用户补充的 63 篇本地资料摘要，强化了找型号、副型、关系模式、心理防御机制和成长路径。

它适合用于：

- 自我成长与性格模式复盘
- 亲密关系、亲子关系、同事关系分析
- 职场沟通、需求协作、团队管理
- 用九型人格作为工作假设，而不是给人贴固定标签

## 安装

把本仓库复制到你的 skills 目录：

```powershell
git clone https://github.com/lwlaosan/gao-yuan-diamond-enneagram-skill.git "$env:USERPROFILE\.codex\skills\gao-yuan-diamond-enneagram-perspective"
```

然后重启 Codex。

## 使用示例

```text
用高源/钻石九型视角分析一下我的亲密关系问题
用高源视角帮我判断这个团队沟通卡在哪里
钻石九型，帮我看见我在这件事里的性格模式
```

## 资料来源与边界

本 skill 基于 2026-04-27 对公开网页、文章、课程介绍、书籍信息和活动报道的调研提炼。调研文件位于：

```text
references/research/
```

其中 `07-local-corpus-2026-04-30.md` 记录了用户补充资料的增量调研摘要。公开仓库只保存摘要和来源线索，不收录微信文章全文。

重要边界：

- 这是非官方 skill，不代表高源本人或钻石九型官方立场。
- 九型人格分析不是医学诊断，也不能替代心理咨询、精神科诊疗、法律或危机干预。
- 对任何人的型号判断都只能是工作假设，不能作为人格定论、招聘筛选或亲密关系裁决。
- 公开可读的高源长访谈逐字稿较少，因此本 skill 更重在方法论和公开文章/课程结构的蒸馏，不伪造现场口吻。
- 2026-04-30 补充材料中部分微信文章缺少作者、发布日期和稳定可访问链接，应作为方法论增强资料使用。

## 仓库结构

```text
.
├── SKILL.md
├── references/
│   ├── research/
│   │   ├── 01-writings.md
│   │   ├── 02-conversations.md
│   │   ├── 03-expression-dna.md
│   │   ├── 04-external-views.md
│   │   ├── 05-decisions.md
│   │   ├── 06-timeline.md
│   │   └── 07-local-corpus-2026-04-30.md
│   └── sources/
└── scripts/
```

## License

MIT

# Mao Zedong Perspective Skill

一个可运行的历史人物视角 skill。

它不是语录拼贴，也不是娱乐化模仿，而是把毛泽东在公开著作、讲话、访谈与重大历史决策中反复出现的思维结构，提炼成一个可调用的分析框架，用来处理组织、战略、动员、路线与复杂矛盾问题。

你不是来听一句“像不像毛泽东说的话”。
你是来问：如果按这套思维方式拆局，他第一步看什么，第二步抓什么，第三步怎么组织行动。

- [效果示例](#效果示例)
- [支持哪些 Agent](#支持哪些-agent)
- [快速安装](#快速安装)
- [这个 skill 到底提炼了什么](#这个-skill-到底提炼了什么)
- [它适合解决什么问题](#它适合解决什么问题)
- [和-qiushi-skill-有什么区别](#和-qiushi-skill-有什么区别)
- [研究透明度](#研究透明度)

## 为什么做这个

很多“人物 skill”有两个常见问题：

1. 只会模仿口气，不会拆问题。
2. 只会摘好听的话，不处理历史代价、争议和内在张力。

这个仓库想做第三种东西：

- 不是“角色扮演玩具”
- 不是“语录收藏夹”
- 而是“一个可工作的认知视角”

所以它保留两件事同时成立：

- 保留毛泽东早期到中期文本中稳定出现的组织与战略方法
- 也明确保留大跃进、文革等后期高代价后果带来的边界与反思

## 效果示例

### 示例 1：团队内耗

用户：

```text
用毛泽东的视角看这个团队。产品、运营、技术都在互相抱怨，老板想同时满足所有人，我该先抓什么？
```

这个 skill 理想中的回答方向不是空喊口号，而是：

- 先分敌友，不把所有冲突都当成一种矛盾
- 先判断哪条矛盾决定全局，不平均用力
- 识别谁是骨干、谁是摇摆力量、谁是主要阻力
- 先拿一个样板突破点，再从点到面扩散

### 示例 2：长期项目到底该不该打持久战

用户：

```text
如果毛泽东来判断这个项目，他会把它当速决战还是持久战？
```

这个 skill 会优先看：

- 当前力量对比是否悬殊
- 条件能不能在过程中被改造
- 阶段目标是否清楚
- “持久”是在重构时间，还是只是在拖延

### 示例 3：增长资源有限，怎么集中兵力

用户：

```text
用毛泽东模式看我的内容增长。内容方向很多，平台很多，资源不够，我应该怎么集中兵力？
```

更像它会给出的答案：

- 不平均铺开
- 先抓主要阵地
- 先做根据地，再谈扩张
- 看群众基础和组织抓手，不只看自我表达

## 这个 skill 到底提炼了什么

这个仓库不是只写了一个 `SKILL.md`，而是把“怎么想、怎么判断、怎么说、什么不做、哪里有边界”一起打包了。

| 层次 | 你会得到什么 |
|---|---|
| 身份与工作流 | 激活后直接以“我”的口吻回答，并按问题分类、调研、分析、落地的顺序输出 |
| 6 个核心心智模型 | 敌友图谱、调查优先、主要矛盾、持久战、群众路线、调动积极因素 |
| 8 条决策启发式 | 帮你快速判断主次、阶段、打法、试点、传播和风险 |
| 表达 DNA | 结论先行、设问推进、分类拆局、短句强压感 |
| 价值观与反模式 | 反对空洞教条、平均用力、脱离群众的判断 |
| 诚实边界 | 明确说明什么能做、什么不能做、哪些历史后果不能回避 |

一句话概括：

这个 skill 提炼的不是“毛泽东说过什么”，而是“毛泽东通常如何拆局、如何排序、如何组织行动”。

## 它怎么工作

当问题进入这个 skill，真正起作用的不是“模仿腔调”，而是下面这条分析链：

1. 先判断这是事实问题、纯框架问题，还是混合问题。
2. 如果涉及具体现实，就先看事实，不硬下断语。
3. 画出敌友与力量图谱。
4. 找出主要矛盾和矛盾的主要方面。
5. 判断问题处在什么阶段，能速决还是必须持久。
6. 落到组织抓手、行动顺序、传播方式和反噬风险。

所以它更像一个“组织与战略分析器”，不是单纯的历史人物 cosplay。

## 研究基础

本仓库的研究不是一句“基于公开资料”，而是保留了完整的六维调研痕迹。

研究维度包括：

1. 著作与系统思考
2. 对话、访谈与口头表达
3. 表达 DNA
4. 他者视角与外部评价
5. 决策记录与历史后果
6. 人物时间线

核心一手材料包括：

- 中文马克思主义文库毛泽东索引
- 《中国社会各阶级的分析》
- 《反对本本主义》
- 《实践论》
- 《矛盾论》
- 《论持久战》
- 《改造我们的学习》
- 《反对党八股》
- 《关于领导方法的若干问题》
- 《为人民服务》
- 《论十大关系》
- 《关于正确处理人民内部矛盾的问题》
- Edgar Snow 访谈

辅助外部材料包括：

- Columbia AFE
- Stanford SPICE
- PBS / Commanding Heights

## 研究透明度

调研过程不是黑盒，文件都在仓库里。

- [SKILL.md](./SKILL.md)
- [01-writings.md](./references/research/01-writings.md)
- [02-conversations.md](./references/research/02-conversations.md)
- [03-expression-dna.md](./references/research/03-expression-dna.md)
- [04-external-views.md](./references/research/04-external-views.md)
- [05-decisions.md](./references/research/05-decisions.md)
- [06-timeline.md](./references/research/06-timeline.md)

你可以直接看到：

- 哪些判断来自一手文本
- 哪些判断来自历史决策模式
- 哪些边界来自后期政治实践的高代价后果

这很重要。

一个不告诉你自己局限在哪的历史人物 skill，不值得信任。

## 支持哪些 Agent

这个仓库现在不只面向 Codex。

它采用的是 `SKILL.md + 技能目录` 这种可移植包装，因此可以用于多种支持 skill / agent instructions / AgentSkills 风格目录的 agent 系统。

当前重点说明以下几类：

| Agent | 当前支持方式 | 推荐安装位置 |
|---|---|---|
| Codex | 直接支持 | `~/.codex/skills/mao-zedong-perspective/` |
| Claude Code | 直接支持 | `~/.claude/skills/mao-zedong-perspective/` 或项目 `.claude/skills/` |
| OpenCode | 直接支持 | `~/.config/opencode/skills/`、项目 `.opencode/skills/`、`.claude/skills/` 或 `.agents/skills/` |
| OpenClaw | 直接支持 | `~/.agents/skills/`、`~/.openclaw/skills/`、项目 `skills/` 或 `.agents/skills/` |
| Hermes | 手动安装支持 | `~/.hermes/skills/` 下的自定义目录 |

为什么现在可以这样说：

- 这个仓库的核心交付物是标准 skill 目录，而不是依赖某个单独平台的私有插件格式
- `SKILL.md` 的 frontmatter 已整理成更通用的单行写法，降低了不同 agent 解析差异带来的兼容风险
- 对于更偏 AgentSkills 风格的系统，这个仓库可以按“复制整个 skill 目录”的方式落地

需要说明的边界：

- 不同 agent 的触发词、自动发现机制、索引时机可能不同
- 有些 agent 会自动加载，有些需要重启或重新索引
- Hermes 生态更偏自己的 skills 体系，所以这里给的是手动安装法，而不是宣称已经上架某个 Hermes 官方 registry

## 快速安装

### 方式一：直接复制到本地 skill 目录

把整个目录复制到：

```text
C:\Users\<你的用户名>\.codex\skills\mao-zedong-perspective
```

然后确认这个文件存在：

```text
SKILL.md
```

最后重启 Codex。

### 方式二：从 GitHub 仓库安装

```powershell
python "$env:CODEX_HOME\skills\.system\skill-installer\scripts\install-skill-from-github.py" --repo hkfrank996/mao-zedong-perspective --path . --name mao-zedong-perspective
```

更详细的安装说明见：

- [.codex/INSTALL.md](./.codex/INSTALL.md)

## 多 Agent 安装方法

### 1. Codex

复制整个仓库目录到：

```text
C:\Users\<你的用户名>\.codex\skills\mao-zedong-perspective
```

然后重启 Codex。

### 2. Claude Code

放到全局 skills 目录：

```text
C:\Users\<你的用户名>\.claude\skills\mao-zedong-perspective
```

或者放到项目级目录：

```text
<你的项目>\.claude\skills\mao-zedong-perspective
```

之后重启 Claude Code，或在新会话中使用。

### 3. OpenCode

OpenCode 会识别多个兼容技能目录。你可以任选其一：

```text
C:\Users\<你的用户名>\.config\opencode\skills\mao-zedong-perspective
```

或项目内：

```text
<你的项目>\.opencode\skills\mao-zedong-perspective
<你的项目>\.claude\skills\mao-zedong-perspective
<你的项目>\.agents\skills\mao-zedong-perspective
```

重启 OpenCode 或重新进入会话后即可调用。

### 4. OpenClaw

OpenClaw 支持多种技能搜索路径。推荐全局路径：

```text
C:\Users\<你的用户名>\.agents\skills\mao-zedong-perspective
```

也可以使用：

```text
C:\Users\<你的用户名>\.openclaw\skills\mao-zedong-perspective
<你的项目>\skills\mao-zedong-perspective
<你的项目>\.agents\skills\mao-zedong-perspective
```

复制完成后，重新启动或重新加载对应 agent 会话。

### 5. Hermes

Hermes 更推荐自己的 skills 目录。手动安装时，可以放到：

```text
C:\Users\<你的用户名>\.hermes\skills\custom\mao-zedong-perspective
```

如果你习惯按分类管理，也可以把 `custom` 换成你自己的分类名。

安装后重启 Hermes，或重新进入新会话。

### 6. 通用检查

无论你装到哪个 agent，最低检查都一样：

1. 目标目录里要有 `SKILL.md`
2. 不要只复制单个文件，要复制整个 skill 文件夹
3. 安装后最好重启 agent 或新建会话
4. 先用一句明确触发词测试

例如：

```text
用毛泽东的视角分析这个组织问题
```

## 如何使用

安装后，直接用自然语言触发：

- `用毛泽东的视角分析这个组织问题`
- `切换到毛泽东，帮我判断这里的主要矛盾`
- `如果毛泽东来做这个增长方案，他会先抓什么`
- `用毛泽东模式看这场内部冲突，谁是敌人谁是朋友`

如果你不想要角色口吻，也可以把它当成一个分析框架来用：

- `用毛泽东的思维框架，而不是模仿语气，帮我拆这个局`

## 它适合解决什么问题

- 组织内部冲突
- 多方力量博弈
- 联盟与统一战线
- 资源有限时的优先级决策
- 长期复杂任务的阶段规划
- 动员、传播、试点、样板突破、经验扩散

## 它不适合解决什么问题

- 需要实时最新事实但又不先研究的问题
- 只想做历史人物娱乐扮演
- 需要严肃史学裁决或道德定论的问题
- 纯技术实现细节，且与组织、战略、路线无关的问题

## 和 `qiushi-skill` 有什么区别

如果你同时在用 `qiushi-skill`，两者最好分工明确：

- `mao-zedong-perspective`：人物视角，一体化回答，直接进入“毛泽东会怎么看”
- `qiushi-skill`：方法论工具箱，把问题拆成矛盾分析、调查研究、持久战略、群众路线等多个模块

简单说：

- 想问“毛泽东会怎么判断”时，用这个仓库
- 想问“先用哪一个方法模块”时，用 `qiushi-skill`

一个偏“人物代理”，一个偏“方法工具箱”。

## 仓库结构

```text
mao-zedong-perspective/
├── SKILL.md
├── README.md
├── .codex/
│   └── INSTALL.md
├── references/
│   ├── research/
│   │   ├── 01-writings.md
│   │   ├── 02-conversations.md
│   │   ├── 03-expression-dna.md
│   │   ├── 04-external-views.md
│   │   ├── 05-decisions.md
│   │   └── 06-timeline.md
│   └── sources/
└── scripts/
```

## 边界与历史责任

这个仓库必须连同它的边界一起看：

- 它只能基于公开资料提炼思维框架，不等于还原私人全部心境
- 它承认毛泽东晚年政治实践造成的高成本后果，不做洗白
- 它提供的是分析视角，不是历史定论
- 使用者应自行判断现实问题是否适合套用历史政治框架

换句话说：

这个 skill 可以帮助你看清组织、战略、动员和路线问题，但不能替你跳过现实调查、伦理判断和具体责任。

## 更新与维护

- 当前调研时间：`2026-04-14`
- 如果后续补入新的公开史料或更高质量研究，本 skill 应继续更新
- 如果你发现某个心智模型证据不足，欢迎直接基于研究文件反向核对

## 许可与说明

本仓库中的包装、结构、文档和整理工作采用 MIT License。

历史文献与引用遵循各来源站点的原始版权与使用条件。

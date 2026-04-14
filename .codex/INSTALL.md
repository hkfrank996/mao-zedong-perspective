# Install for Multiple Agents

这份安装说明不只适用于 Codex，也适用于支持 skill / agent instructions / AgentSkills 风格目录的其他 agent。

## 先说结论

这个仓库现在可以按“复制整个 skill 目录”的方式，用在以下 agent：

- Codex
- Claude Code
- OpenCode
- OpenClaw
- Hermes

核心前提只有一个：

目标目录里必须最终存在：

```text
mao-zedong-perspective/
└── SKILL.md
```

不要只复制 `SKILL.md` 单文件，要复制整个 skill 目录。

## 1. Codex

推荐路径：

```text
C:\Users\<你的用户名>\.codex\skills\mao-zedong-perspective
```

安装步骤：

1. 下载或克隆这个仓库
2. 把整个目录复制到上面的路径
3. 重启 Codex

验证方式：

```text
用毛泽东的视角分析这个组织问题
```

## 2. Claude Code

全局路径：

```text
C:\Users\<你的用户名>\.claude\skills\mao-zedong-perspective
```

项目路径：

```text
<你的项目>\.claude\skills\mao-zedong-perspective
```

安装步骤：

1. 下载或克隆这个仓库
2. 复制整个目录到全局或项目级 skills 目录
3. 重启 Claude Code，或重新开始一个新会话

## 3. OpenCode

OpenCode 会识别多个兼容目录，你可以任选一种：

全局路径：

```text
C:\Users\<你的用户名>\.config\opencode\skills\mao-zedong-perspective
```

项目路径：

```text
<你的项目>\.opencode\skills\mao-zedong-perspective
<你的项目>\.claude\skills\mao-zedong-perspective
<你的项目>\.agents\skills\mao-zedong-perspective
```

安装步骤：

1. 下载或克隆这个仓库
2. 复制整个目录到任一 OpenCode 支持的目录
3. 重启 OpenCode 或重新进入会话

## 4. OpenClaw

OpenClaw 支持多种搜索路径。

推荐全局路径：

```text
C:\Users\<你的用户名>\.agents\skills\mao-zedong-perspective
```

也可使用：

```text
C:\Users\<你的用户名>\.openclaw\skills\mao-zedong-perspective
<你的项目>\skills\mao-zedong-perspective
<你的项目>\.agents\skills\mao-zedong-perspective
```

安装步骤：

1. 下载或克隆这个仓库
2. 复制整个目录到任一路径
3. 重启 OpenClaw，或重新进入目标 agent 会话

说明：

为了减少兼容问题，仓库中的 `SKILL.md` frontmatter 已整理为更通用的单行写法，更适合 OpenClaw 这类对 frontmatter 更严格的解析器。

## 5. Hermes

Hermes 可以使用手动安装方式。

推荐路径：

```text
C:\Users\<你的用户名>\.hermes\skills\custom\mao-zedong-perspective
```

如果你习惯自己分类，也可以把 `custom` 换成别的分类目录名。

安装步骤：

1. 下载或克隆这个仓库
2. 把整个目录复制到 `~/.hermes/skills/` 下的某个分类目录中
3. 重启 Hermes，或重新开始新会话

## 6. 从 GitHub 安装到 Codex

如果你的 Codex 已内置 `skill-installer`，可以直接执行：

```powershell
python "$env:CODEX_HOME\skills\.system\skill-installer\scripts\install-skill-from-github.py" --repo hkfrank996/mao-zedong-perspective --path . --name mao-zedong-perspective
```

## 7. 通用验证步骤

不管装到哪个 agent，都建议做这四步：

1. 确认目录存在
2. 确认 `SKILL.md` 在最终路径下
3. 重启 agent 或新建会话
4. 用明确触发词测试

测试句：

```text
用毛泽东的视角分析这个组织问题
```

或：

```text
切换到毛泽东，帮我判断这里的主要矛盾
```

## 8. 常见问题

### 1. 为什么复制后没生效

最常见原因：

- 目录层级多了一层
- 只复制了 `SKILL.md`
- 安装后没有重启 agent
- 你的 agent 没有扫描到你放置的那个 skills 目录

### 2. 它真的不是只支持 Codex 吗

不是。

这个仓库本质上是一个可移植的 skill 目录，只要目标 agent 支持 `SKILL.md` 风格或兼容 AgentSkills 式目录，就可以手动安装使用。

### 3. 不同 agent 的效果会完全一样吗

不一定。

底层技能内容是同一个，但不同 agent 的：

- 自动发现机制
- 触发方式
- 会话记忆
- 指令优先级

都可能不同，所以实际表现会有差异。

### 4. 如果我要卸载

直接删除对应目录即可，然后重启目标 agent。

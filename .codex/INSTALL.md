# Install for Codex

这份安装说明尽量按“复制就能做”的方式写。

## 你会安装到哪里

默认目标目录：

```text
C:\Users\<你的用户名>\.codex\skills\mao-zedong-perspective
```

安装完成后，最关键的是这里要存在：

```text
SKILL.md
```

## 方式一：直接复制

这是最稳的方式。

1. 下载或克隆这个仓库
2. 把整个 `mao-zedong-perspective` 目录复制到：

```text
C:\Users\<你的用户名>\.codex\skills\
```

3. 确认最终路径长这样：

```text
C:\Users\<你的用户名>\.codex\skills\mao-zedong-perspective\SKILL.md
```

4. 重启 Codex

## 方式二：从 GitHub 安装

如果你的 Codex 已经带有系统 skill `skill-installer`，可以直接运行：

```powershell
python "$env:CODEX_HOME\skills\.system\skill-installer\scripts\install-skill-from-github.py" --repo hkfrank996/mao-zedong-perspective --path . --name mao-zedong-perspective
```

如果你的环境里 `CODEX_HOME` 没生效，也可以把路径替换成你自己的 Codex 安装目录。

## 安装后怎么验证

安装完成后，检查这三件事：

1. 目录存在：

```text
C:\Users\<你的用户名>\.codex\skills\mao-zedong-perspective
```

2. 主文件存在：

```text
SKILL.md
```

3. 重启 Codex 后，直接试一句：

```text
用毛泽东的视角分析这个组织问题
```

如果能触发人物视角回答，说明安装成功。

## 常用触发示例

- `用毛泽东的视角分析这个组织问题`
- `切换到毛泽东`
- `如果毛泽东来做这个项目，他会先抓什么`
- `用毛泽东模式判断这里的主要矛盾`
- `用毛泽东的思维框架，而不是模仿语气，帮我拆这个局`

## 卸载方式

如果你不想用了，直接删除这个目录即可：

```text
C:\Users\<你的用户名>\.codex\skills\mao-zedong-perspective
```

然后重启 Codex。

## 更新方式

如果仓库有新版本，推荐做法：

1. 删除旧目录
2. 重新复制新版目录，或重新运行 GitHub 安装命令
3. 重启 Codex

## 常见问题

### 1. 为什么复制后没生效

最常见原因有三个：

- 目录层级多了一层，导致 `SKILL.md` 不在预期位置
- 只复制了单个文件，没有复制整个 skill 目录
- 安装后没有重启 Codex

### 2. 它会默认娱乐化扮演吗

不会。

这个 skill 的目标是“用毛泽东的思维框架分析问题”，不是做低质量模仿秀。仓库也明确保留了历史边界和后期高代价后果，不是洗白型包装。

### 3. 它和 `qiushi-skill` 冲突吗

不冲突。

- 这个仓库更像“人物视角代理”
- `qiushi-skill` 更像“方法论工具箱”

两个可以并存，按场景分别调用。

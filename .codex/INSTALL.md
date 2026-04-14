# Install for Codex

安装方式有两种。

## 方式一：直接复制

把整个目录复制到：

```text
C:\Users\<你的用户名>\.codex\skills\mao-zedong-perspective
```

确保下面这个文件存在：

```text
SKILL.md
```

然后重启 Codex。

## 方式二：从 GitHub 安装

如果你已经把仓库发布到 GitHub，可以用 Codex 的 `skill-installer`：

```powershell
python "$env:CODEX_HOME\skills\.system\skill-installer\scripts\install-skill-from-github.py" --repo <owner>/mao-zedong-perspective --path . --name mao-zedong-perspective
```

## 触发示例

- `用毛泽东的视角分析这个组织问题`
- `切换到毛泽东`
- `如果毛泽东来做这个项目，他会先抓什么`
- `用毛泽东模式判断这里的主要矛盾`

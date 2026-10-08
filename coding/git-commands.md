# Git 常用命令

<p class="note-meta">📅 2026-10-08 · 🏷 编程基础</p>

## 一句话总结

> Git 是"代码的存档系统"，可以随时回到任何一个历史版本。

## 速查表

| 命令 | 作用 |
|---|---|
| `git clone <地址>` | 把远程仓库下载到本地 |
| `git status` | 查看哪些文件改动了 |
| `git add .` | 把所有改动加入暂存区 |
| `git commit -m "说明"` | 存档一次 |
| `git push` | 上传到 GitHub |
| `git pull` | 从 GitHub 拉取最新内容 |
| `git log --oneline` | 查看存档历史 |

## 一次完整的提交流程

```bash
git add .
git commit -m "新增 Python 笔记"
git push
```

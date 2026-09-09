# Git 学习笔记

## 基础概念

- Git 是版本管理工具，用来记录文件的修改历史，方便回退和多人协作。
- GitHub 是基于 Git 的代码托管平台，用来托管和分享仓库。
- 基本流程：工作区 → 暂存区（git add）→ 本地仓库（git commit）→ 远程仓库（git push）。

## 我实际用过的命令

| 命令 | 作用 |
|------|------|
| `git config --global user.name "..."` | 配置用户名 |
| `git config --global user.email "..."` | 配置邮箱 |
| `git config --global http.proxy ...` | 配置代理（国内访问 GitHub 需要） |
| `git clone <url>` | 克隆远程仓库到本地 |
| `git status` | 查看当前文件状态 |
| `git add <file>` | 把文件加入暂存区 |
| `git commit -m "说明"` | 提交暂存区的改动 |
| `git push` | 推送到远程仓库 |
| `git log` | 查看提交历史 |

## 学习心得

- commit message 要写清楚「改了什么」，别用 update、final 这种模糊描述。
- 国内访问 GitHub 需要配置代理（我用的 Clash，端口 7897）。
- 从命令行推送到 GitHub 需要 Personal Access Token，而不是账号密码。
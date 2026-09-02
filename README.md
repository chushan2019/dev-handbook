# dev-handbook

个人开发工具手册库。存放日常开发中反复查阅的技术手册、速查卡与写作模板，按「主题域」分目录组织。

## 手册索引

| 主题 | 文件 | 版本 | 状态 |
|---|---|---|---|
| Git 分支与 Worktree | [git/git-branch-worktree-guide.html](git/git-branch-worktree-guide.html) | v1.0 | ✅ 已定稿 |

## 目录结构

```
dev-handbook/
├── README.md            ← 本文件：总索引
├── git/                 ← Git 主题手册
├── cheatsheets/         ← 速查卡（高频查阅，独立成页/PDF）
├── templates/           ← 手册写作模板（保证格式统一）
└── assets/              ← 图片、logo 等静态资源
```

## 命名规范

- 文件名：语义化小写 + 短横线，如 `git-branch-worktree-guide.html`
- 版本信息**不写进文件名**，用 `git tag` 标记（如 `v1.0`）

## 在线访问

- 主站（GitHub Pages）：<https://chushan2019.github.io/dev-handbook/>
- 仓库源码：<https://github.com/chushan2019/dev-handbook>

## 使用方式

- 完整学习：打开对应主题目录下的 `.html` 文件，或访问上面的 Pages 主站
- 高频查阅：优先看 `cheatsheets/` 下的速查卡
- 检索：`Cmd+F` 全文搜索，或 GitHub 网页端搜索

## 权限与贡献

- **本仓库为公开（public）**：任何人都可浏览、克隆、提 Issue 或发 PR。
- **直接 push 仅限仓库所有者（owner）**：陌生人无法直接向 `main` 分支提交代码；PR 只有在我（owner）点击 Merge 后才会合入。
- 若未来希望更严格的流程，可开启分支保护规则（Branch Protection），强制「所有改动先走 PR 并 review」。

## 版本策略

- 定稿 → 打 tag（`git tag v1.0`）
- 内容大改 → 升大版本（`v2.0`），小修 → 升小版本（`v1.1`）
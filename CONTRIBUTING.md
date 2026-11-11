# 贡献指南 (Contributing to RootedVox)

首先，感谢你愿意为 RootedVox 贡献力量！为了保证代码质量和双端部署的稳定性，请遵循以下规范：

## 1. 报告问题 (Issues)
*   在提交 Issue 之前，请先搜索是否已经有人提出过相同的问题。
*   请使用清晰的标题，并详细描述复现步骤、预期结果和实际结果。

## 2. 提交代码 (Pull Requests)
*   **分支规范**：请基于 `main` 分支创建新的特性分支，例如 `feature/add-comment` 或 `fix/login-bug`。
*   **双端适配**：由于本项目是 CF 与 Vercel 双端部署，如果你修改了后端接口，请务必确保同时在 CF 的 `functions/` 和 Vercel 的 `api/` 目录下进行兼容性修改。
*   **代码风格**：请确保代码通过 ESLint 和 Prettier 的检查。
*   **提交信息**：请使用 Conventional Commits 规范（如 `feat: 增加留言板功能`，`fix: 修复鉴权跳转问题`）。

## 3. 环境变量
**绝对不要**将包含真实密钥的 `.env` 文件提交到 Git 仓库中。

## 4. 行为准则
*   保持友善和尊重，禁止任何形式的人身攻击或歧视性言论。

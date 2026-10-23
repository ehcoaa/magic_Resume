# Magic Resume · 社区二次开发版

> 本仓库由 [BinYuanc](https://github.com/BinYuanc) 基于 [JOYCEQL/magic-resume](https://github.com/JOYCEQL/magic-resume) 维护与修改。这里的使用说明以本仓库为准，并非上游项目的官方发布页。

## 项目用途

用于在浏览器中编辑和预览个人简历，支持主题调整、PDF 导出等简历制作场景。仓库包含 AI 辅助编辑相关实现；具体能力及兼容性请以当前代码和实际运行结果为准。

## 安装与启动

需要 Node.js 和 pnpm。克隆**本仓库**：

```bash
git clone https://github.com/BinYuanc/magic_Resume.git
cd magic_Resume
pnpm install
pnpm dev
```

按终端提示打开本地页面（通常为 http://localhost:3000）。

Windows 用户可尝试仓库根目录的 `start-magic-resume.vbs` / `start-magic-resume.bat`；如启动失败，请先通过命令行启动并查看报错。

Docker 用户可按仓库现有配置尝试 `docker compose up -d`，部署前请自行检查环境变量与网络连通性。

## 当前维护状态与已知限制

- **功能验证范围**：本说明尚未完成逐功能运行回归；请勿将仓库中出现的功能代码等同于已经验证可用。
- **AI 服务**：通常需要自行配置对应服务的 API 凭据；模型服务可用性、代理设置及费用取决于用户环境。
- **浏览器导出与排版**：不同浏览器、字体及纸张设置可能影响 PDF 的分页与排版；建议导出后人工检查。
- **Windows 一键启动**：依赖本机运行环境与端口状态；如有异常，请使用 `pnpm dev` 定位。
- **待确认 Bug**：尚未建立基于复现步骤、影响版本和日志的已确认 Bug 清单。欢迎通过 Issues 提交可复现问题，避免将未经核实的猜测写成已知故障。

## 问题反馈

请在 [本仓库 Issues](https://github.com/BinYuanc/magic_Resume/issues) 提交：运行系统、启动方式、复现步骤、预期/实际结果及脱敏日志。不要公开上传简历隐私或 API Key。

## 二次开发与版权说明

原始项目：[JOYCEQL/magic-resume](https://github.com/JOYCEQL/magic-resume)。感谢原项目作者及贡献者。本仓库不是原作者的官方版本；原项目的联系方式、赞助信息与收款入口不代表本仓库维护者。

**许可注意**：仓库 `LICENSE` 包含 Apache 2.0 相关表述及额外商业使用限制。该组合的法律效力及商业授权边界应以适用法律和权利人授权为准；请在商用或再分发前自行核实，勿仅凭 README 判断可商用。

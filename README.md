# 开源项目与贡献

## [Vocabulary-constrained reading](https://github.com/LiuHangyuWE/vocabulary-constrained-reading) · 我的项目

我发布的英语阅读 Agent Skill，根据学习者已有词汇表调整英文原文，以尽可能小的改动减少陌生词汇负担。

- **保留真实句法**：重点调整生词，尽量保留原文的长句、从句结构、信息和语气；词汇已知的句子默认不改。
- **按个人词表适配**：支持用户提供的词汇列表与配置，结合上下文选择自然的替换表达，并提供单独的改写审阅流程。
- **可复用的 Skill 包**：提供使用说明、示例、可选的词表处理工具和测试，以及中英文文档。

使用与安装见[中文文档](https://github.com/LiuHangyuWE/vocabulary-constrained-reading/blob/main/README.zh-CN.md)。

## [ClaudeViewer](https://github.com/crownleo/ClaudeViewer) · 参与贡献

用于在本地离线查看和管理 Claude 导出记录的开源工具。

我的贡献：

- **档案管理方案**：参与原件保留、多档案切换和收藏／标签隔离的设计，让不同账号、不同日期的导出独立保存，并能完整取出原始文件。
- **可选 macOS 应用**：贡献基于 AppKit / WebKit 的桌面外壳和本机档案存储，复用网页版的解析与展示功能，兼容旧版完整 ZIP 和新版 manifest 加多个 ZIP 的导出格式。
- **构建与验证**：提供源码构建脚本和自动化测试，并在 Apple Silicon Mac 上完成构建与实机验证。

macOS 伴侣已于 **2026 年 9 月 9 日**通过 [PR #4](https://github.com/crownleo/ClaudeViewer/pull/4) 合入原项目。最初的档案管理方案与讨论见 [PR #3](https://github.com/crownleo/ClaudeViewer/pull/3)，相关贡献也记录在[项目致谢](https://github.com/crownleo/ClaudeViewer#-致谢)中。

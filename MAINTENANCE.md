# GitGuide 维护说明

Git 工作流、提交信息和 README 规范的 MkDocs 文档。

- 上游：https://github.com/ZJDoc/GitGuide
- 在线文档：https://xiaoshecode.github.io/xiaoshecode/repos/GitGuide/
- 检查日期：2026-10-30

## 环境与使用

- python -m pip install -r docs/requirements.txt

使用/检查入口（需先满足依赖条件）：

- `python -m mkdocs serve`
- `python -m mkdocs build`

## 目录职责

- docs/ — 指南正文
- mkdocs.yml — 导航与主题
- docs/requirements.txt — 文档依赖
- templates/ — 示例模板

## 本次整理

- 新增维护文档和在线文档入口，补全用途、目录、使用路径及验证边界。

## 检查记录

- **仓库目录与入口盘点**（passed）：检查 Git 索引中的 74 个路径、README 和项目配置；不等于功能验收。
- **XML parse**（passed）：1 个文件通过解析；不导入依赖、不执行应用。
- **完整构建与端到端运行**（not_run）：本次检查目录、配置引用和文档入口；未安装历史 MkDocs 主题版本或构建上游站点。

## 验证边界与待办

- 本次检查目录、配置引用和文档入口；未安装历史 MkDocs 主题版本或构建上游站点。

## 后续维护约定

保留上游许可证与作者信息。沿用现有模块边界和格式配置；修复功能时同步最小回归验证。依赖或接口变更需写明迁移步骤，避免仅为目录美观搬动公开入口。

# 商品自动下架规则中心 (Auto Delisting Rule Center)

这是一个商品自动下架规则管理系统的高保真交互原型，包含规则配置、白名单管理、批量导入等核心功能。

## 📦 项目内容

*   `index.html`: 核心原型文件 (V2.0)，包含所有 HTML/CSS/JS 代码。
*   `PRD_Auto_Delisting_Rule_Center_V1.5.md`: 最终版产品需求文档。

## 🚀 在线预览

你可以通过以下方式预览本项目：

1.  **本地预览**: 双击打开 `index.html`。
2.  **GitHub Pages (推荐)**: 
    *   Fork 或 Push 本项目到你的 GitHub。
    *   进入 Settings -> Pages。
    *   选择 Branch: `main` / Folder: `root` 并保存。
    *   访问生成的 `https://yourname.github.io/repo-name/` 链接。

## ✨ 核心功能 (V2.0)

1.  **规则配置**:
    *   支持配置 `错误码阻断`、`高频失败熔断`、`累计失败熔断` 等策略。
    *   实现了策略互斥逻辑（同类型策略只能添加一条）。
    *   支持规则的启用/禁用状态切换。

2.  **白名单管理 (Pro)**:
    *   管控维度升级为 `店铺ID + SKU ID`。
    *   **批量添加**: 支持从 Excel 直接复制两列数据粘贴，系统自动解析并去重。

3.  **交互体验**:
    *   Tab 分页设计，无缝切换功能模块。
    *   完善的表单校验与 Toast 实时反馈。

## 🛠️ 技术栈

*   纯原生 HTML5 / CSS3 / JavaScript (ES6+)。
*   无外部依赖，开箱即用。

---
*Created by Trae AI Pair Programmer*

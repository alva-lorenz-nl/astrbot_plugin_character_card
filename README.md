# AstrBot 角色卡生成器 (Character Card Generator)

快速生成适配 AstrBot 的沉浸式角色卡与破甲/偏爱提示词模板，支持聊天指令交互与后台 WebUI 可视化配置。

## 功能特性

- **聊天指令快速生成**：使用 `/生成角色卡` 指令即可按规范生成标准角色卡。
- **管理面板 WebUI**：集成在 AstrBot 管理面板，提供可视化表单、实时预览与一键复制。
- **预设快速填充**：内置示例模板，方便快速理解字段结构。
- **规范结构输出**：自动排版 Character-driven 指南、人设信息、偏爱机制与对话要求。

## 安装方式

在 AstrBot 插件管理页面直接安装，或克隆至 `data/plugins/` 目录：

```bash
cd data/plugins
git clone https://github.com/alva-lorenz-nl/astrbot_plugin_character_card.git
```

## 使用方法

### 1. 指令方式
- `/生成角色卡 名字=赫尔曼·塞曼, 身份=永动轮前CEO, 性格=严谨偏执, 关系=前同事`
- `/生成角色卡 示例` 查看快速用法

### 2. WebUI 方式
打开 AstrBot 后台管理面板 -> 左侧插件管理 -> 点击「角色卡生成器」页面，在表单中填写各项设定并点击生成即可。

<div align="center">

# 🧬 【S.012】Starryear-Clone｜星年·克隆

**让同一张照片中的两个不同主体，分别在上下空间里缩小、复制、倒置。**

![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=for-the-badge&logo=openai&logoColor=white)
[![Usage](https://img.shields.io/badge/Usage-Personal%20%26%20Non--commercial-lightgrey?style=for-the-badge)](./LICENSE.md)
![Language](https://img.shields.io/badge/🌐_中文-English-blue?style=for-the-badge)

</div>

---

## ⚠️ 声明

> **仅限个人学习、非营利研究与非商业创作。**
> 任何商业使用均须事先取得 Starryear年 的书面许可。
>
> 分享作品时，欢迎标注来源并 **@Starryear年**。

---

## 📖 关于本项目

本 Skill 将一张照片制作成无文字竖版三联画：中间保留未经生成的原片证据，上层选择主体 A 做缩小、复制与倒置，下层改选不同的主体 B 执行同一方法，并通过不同镜头与空间边界形成两种超现实事件。

- ✅ 支持人物、动物、车辆、植物、栏杆、船、路灯、建筑模块等双主体组合
- ✅ 强制保留富士山、小船、地标、天际线等决定场景身份的证据
- ❌ 不把上下两层做成同一主体、同一构图或普通复制粘贴

> 📝 The Skill includes the complete prompt in both **Chinese** and **English**.

---

## 🖼️ 示例作品

> 测试通过后补充。当前 `assets/examples/` 保持为空，不放置参考图、测试图或临时生成图。

---

## 📋 目录

- [使用方法](#-使用方法)
- [可自由调整的部分](#-可自由调整的部分)
- [核心原则](#-核心原则)
- [内容结构](#-内容结构)
- [许可证](#-许可证)

---

## 🚀 使用方法

### 方式一：作为 Codex Skill 使用

1. 将整个 `starryear-dual-subject-clone` 文件夹复制到 Codex skills 目录，例如 `~/.codex/skills/`。
2. 开启新的 Codex 对话并上传一张照片。
3. 提出需求：

   > 使用 `starryear-dual-subject-clone`，上层复制倒置人物，下层复制倒置红栏杆。

4. Skill 返回一张无文字、无边框的竖版 2:3 三联画。

### 方式二：作为提示词直接使用

| 语言 | 文件 |
| :---: | :--- |
| 🇨🇳 中文 | [references/starryear-dual-subject-clone-prompt.zh-CN.md](references/starryear-dual-subject-clone-prompt.zh-CN.md) |
| 🇬🇧 English | [references/starryear-dual-subject-clone-prompt.en.md](references/starryear-dual-subject-clone-prompt.en.md) |

---

## 🎛️ 可自由调整的部分

| 参数 | 说明 |
| :--- | :--- |
| **上下主体** | 可由用户指定，也可自动选择两个轮廓清楚、彼此不同的对象。 |
| **克隆数量** | 上层建议 8–20 个，下层建议 10–22 个；画面复杂时适当减少。 |
| **镜头与空间机制** | 可使用平视、低机位、俯视，以及水面、岩缝、道路、阴影、建筑边界等源图支持的空间关系。 |

---

## 💡 核心原则

1. **不同主体，共享方法** — 上下分别克隆不同对象，但都必须明显缩小、复制并以倒置为主。
2. **证据优先** — 中层保持原图像素，决定场景身份的地标与物件不得因生成而丢失。
3. **空间分化** — 上下层即使遮住全部克隆，也必须在镜头、边界、密度和运动上明显不同。

---

## 📁 内容结构

```text
starryear-dual-subject-clone/
├── README.md
├── LICENSE.md
├── SKILL.md
├── agents/openai.yaml
├── references/
│   ├── starryear-dual-subject-clone-prompt.zh-CN.md
│   └── starryear-dual-subject-clone-prompt.en.md
├── scripts/compose_triptych.py
└── assets/examples/
```

> ⚠️ 初版测试包中的 `assets/examples/` 必须为空。仅在 Starryear年 确认测试通过后，加入其提供或明确认可的最终成品图。

---

## 📄 许可证

本项目采用 [LICENSE.md](./LICENSE.md) 中规定的使用条款。

---

<div align="center">

**如果这个项目对你有帮助，欢迎 Star ⭐ 支持！**

</div>

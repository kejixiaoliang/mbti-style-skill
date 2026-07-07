# MBTI Style Skill

一个用于复刻指定 MBTI IP 形象视觉语言的 Codex Skill。它基于本项目中的参考形象分析，沉淀出低多边形、几何切面、UI 友好角色插画的完整风格规范，方便后续生成同风格 MBTI 人设、头像、吉祥物和小场景插画。

Author / 作者：公众号：科技小亮AGI

## 中文说明

### 这个项目是什么

`mbti-style-skill` 是一个面向 Codex 的风格型 Skill，用于指导 AI 生成同一套 MBTI IP 视觉风格的形象。Skill 内包含：

- `SKILL.md`：Skill 触发说明、使用流程和输出规则
- `references/style-guide.md`：完整风格分析，包括角色比例、低多边形几何语言、色彩、线条、阴影、构图、UI 使用边界、MBTI 类型到视觉 archetype 的映射
- `assets/mbti-ip-contact-sheet.jpg`：参考图总览，用于快速对照整体风格
- `assets/image-metadata.json`：参考图尺寸和文件索引数据
- `agents/openai.yaml`：Codex UI 元数据

### 风格关键词

- 低多边形几何卡通
- faceted paper-cut / 纸雕切面感
- 白底、轻投影、UI 友好
- 简化五官、夸张姿态、强道具识别
- 绿色、青色、紫色、黄色为主的 MBTI 性格色彩体系
- 适合头像、结果卡、onboarding 插画、贴纸、IP 角色设定

### 使用方式

在 Codex 中调用：

```text
Use $mbti-style-skill to create an ENFP creator avatar in the same MBTI low-poly IP style.
```

或提出中文需求：

```text
使用 $mbti-style-skill，帮我做一个同风格的 INTJ 策略家头像。
```

如果手动安装，把 `mbti-style-skill/` 文件夹复制到 Codex skills 目录，例如：

```text
C:\Users\<your-user>\.codex\skills\mbti-style-skill
```

### 目录结构

```text
mbti-style-skill/
  SKILL.md
  agents/
    openai.yaml
  assets/
    image-metadata.json
    mbti-ip-contact-sheet.jpg
  references/
    style-guide.md
```

### 注意

本仓库提交的是整理后的 Skill 成品和必要参考索引，不包含手机原始图片素材目录。后续生成图片时，应使用 Skill 中总结的风格规则，而不是逐像素复制原图。

## English

### What This Project Is

`mbti-style-skill` is a Codex Skill for creating MBTI-style IP characters and mascot illustrations in a consistent low-poly visual language. It turns a local reference image set into a reusable style guide for generating matching MBTI avatars, character concepts, stickers, result-card illustrations, and small UI scenes.

Included files:

- `SKILL.md`: trigger description, workflow, and output rules
- `references/style-guide.md`: full visual analysis covering geometry, color, linework, shadows, composition, UI usage, and MBTI archetype mapping
- `assets/mbti-ip-contact-sheet.jpg`: visual contact sheet for fast style comparison
- `assets/image-metadata.json`: source image index and dimensions
- `agents/openai.yaml`: Codex UI metadata

### Style Keywords

- Low-poly geometric cartoon
- Faceted paper-cut character shapes
- White background, soft ground shadow, UI-friendly composition
- Minimal facial features, expressive posture, readable props
- Green, teal, purple, and yellow MBTI-inspired color families
- Suitable for avatars, result cards, onboarding illustrations, stickers, and character IP design

### Usage

Invoke it in Codex:

```text
Use $mbti-style-skill to create an INTJ strategist avatar in the same MBTI low-poly IP style.
```

Manual installation:

```text
C:\Users\<your-user>\.codex\skills\mbti-style-skill
```

### Note

This repository contains the finished reusable Skill and its compact reference assets. It does not include the original phone image folder. Generated outputs should follow the extracted style system rather than directly copying any source image.

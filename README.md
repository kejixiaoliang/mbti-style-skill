# MBTI Style Skill

一个用于规划并制作 MBTI IP 形象的 Codex Skill。它不是简单的“同风格生图提示词”，而是先把用户给出的一个词、几个词或一组主题，分析成清晰的 IP 设计逻辑，再生成符合 MBTI 低多边形风格的角色提示词和批量设计矩阵。

Author / 作者：公众号：科技小亮AGI

## 中文说明

### 这个项目是什么

`mbti-style-skill` 是一个面向 Codex 的 MBTI IP 角色规划与风格生成 Skill。它基于参考形象总结出低多边形、几何切面、白底轻投影、UI 友好角色插画的视觉规则，并新增了“先规划，再制作”的工作流。

适合这些场景：

- 用户只发一个词或短语，例如“夜猫子选手”“职场显眼包”“冷静观察者”
- 需要先分析词语，再转译成 IP 角色设定
- 需要为单个 MBTI 类型生成头像、贴纸或角色设定
- 需要规划包含多个分类、几十个 IP 的大型角色体系
- 需要批量输出每个 IP 的主色、道具、姿态、构图和最终提示词

### 核心能力

- 短词语义分析：从一个词推导情绪、人格气质、视觉隐喻和角色定位
- MBTI 风格转译：把抽象人格变成低多边形 IP 角色语言
- 单角色提示词生成：输出结构化方案、最终 prompt 和 negative prompt
- 批量 IP 规划：先建立分类体系、主色系统、角色矩阵，再分批制作
- 风格一致性检查：从低多边形、色彩、构图、道具、UI 可用性等角度验收
- 抠图友好约束：角色和主要道具尽量形成一体化连贯轮廓，避免漂浮碎片和零散小元素
- 官方比例约束：保持参考 MBTI 形象的协调比例，避免头过大、四肢过长或身体过碎

### 文件结构

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
    planning-guide.md
    batch-ip-matrix.md
```

### 主要文件

- `SKILL.md`：Skill 入口、触发条件、任务分流和输出规则
- `references/style-guide.md`：完整视觉风格分析，包括几何、色彩、线条、阴影、构图和 MBTI archetype
- `references/planning-guide.md`：单个词或短语的 IP 设计分析流程，例如“夜猫子选手”
- `references/batch-ip-matrix.md`：大型 IP 项目的分类规划、16 型 MBTI 表、批量矩阵和验收规则
- `assets/mbti-ip-contact-sheet.jpg`：参考图总览，用于快速对照整体风格
- `assets/image-metadata.json`：参考图尺寸和文件索引数据

### 使用方式

在 Codex 中调用：

```text
Use $mbti-style-skill，帮我分析“夜猫子选手”，先规划 IP 形象，再写出最终生图提示词。
```

大型项目示例：

```text
Use $mbti-style-skill，帮我规划 36 个职场人格 IP。先做分类、主色、角色矩阵和每个 IP 的提示词，不要直接生图。
```

单个 MBTI 类型示例：

```text
Use $mbti-style-skill to design an INTJ strategist avatar. First analyze the role, then write the final image prompt.
```

### 安装方式

把 `mbti-style-skill/` 文件夹复制到 Codex skills 目录，例如：

```text
C:\Users\<your-user>\.codex\skills\mbti-style-skill
```

### 注意

本仓库提交的是整理后的 Skill 成品和必要参考索引，不包含手机原始图片素材目录。后续生成图片时，应使用 Skill 中总结的风格规则和规划流程，而不是逐像素复制原图。

## English

### What This Project Is

`mbti-style-skill` is a Codex Skill for planning and creating MBTI-style IP characters. It does more than write same-style image prompts: it first analyzes a keyword, phrase, MBTI type, or large theme into a clear IP design logic, then produces structured character plans, prompt matrices, and low-poly visual prompts.

It is useful when:

- The user provides only one keyword or a short phrase
- A concept needs to be translated into an IP character before image generation
- A single MBTI avatar, sticker, or character sheet is needed
- A large set of categorized IP characters needs planning
- Dozens of characters need consistent colors, props, poses, and prompts

### Core Capabilities

- Short keyword analysis: infer mood, personality direction, visual metaphor, and role
- MBTI visual translation: turn abstract personality into low-poly IP design language
- Single-character prompt planning: output design logic, final prompt, and negative prompt
- Batch IP planning: create taxonomy, color systems, character matrices, and production batches
- Style review: check low-poly geometry, color consistency, props, composition, and UI usability
- Cutout-friendly design: keep the body and major props as one connected silhouette with minimal loose fragments
- Official proportion control: keep the compact MBTI mascot feel instead of chibi or realistic human proportions

### Usage

Invoke it in Codex:

```text
Use $mbti-style-skill to analyze "night owl player", plan the IP character, then write the final image prompt.
```

Large project example:

```text
Use $mbti-style-skill to plan 36 workplace personality IP characters. Create categories, color rules, a character matrix, and prompts before generating images.
```

Manual installation:

```text
C:\Users\<your-user>\.codex\skills\mbti-style-skill
```

### Note

This repository contains the finished reusable Skill and its compact reference assets. It does not include the original phone image folder. Generated outputs should follow the extracted style system and planning workflow rather than directly copying any source image.

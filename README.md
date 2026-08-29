# Three-View Emotion Outfit Board Generator
# 三视图情绪穿搭图鉴生成器

[中文](#中文说明) | [English](#english)

> Turn character, outfit and emotion descriptions into consistent three-view fashion boards with matching facial-expression close-ups.
>
> 将人物设定、穿搭描述与情绪表情自动整理成统一的三视图穿搭图鉴与对应面部近景提示词。

## 中文说明

### 这是什么？

这是一个面向图像生成工作流的提示词 Skill。

你只需要提供：

- 统一人物设定
- 每套穿搭描述
- 鞋袜、包袋、配饰
- 对应情绪 / 表情

Skill 会自动整理为可以直接用于生图的完整提示词。

### 默认画面结构

- 上半部分：全身正面、90°侧面、背面三视图
- 下半部分：对应情绪的面部近景
- 白色极简摄影棚背景
- 柔和均匀高调光线
- 真实服装面料与皮肤纹理
- Fashion Lookbook / Character Sheet 图鉴排版

### 适合用来做

- 穿搭图鉴
- 人物三视图
- 情绪表情图鉴
- Character Sheet
- Fashion Lookbook
- 多套穿搭批量提示词

### 使用方法

直接把人物设定、穿搭和表情发给支持 Skill 的 Agent / 模型，例如：

```text
统一基础设定：
年轻成年东亚女性，黑棕色长卷发，白色摄影棚背景，真实摄影质感。

1｜白色吊带 + 牛仔短裤｜傲到抬下巴撇嘴
【服装描述】
【表情描述】

2｜蓝白条纹衬衫 + 黑色短裙｜委屈到泪崩低头
【服装描述】
【表情描述】
```

Skill 会把每套穿搭拆开，并生成独立的“三视图 + 情绪近景”提示词。

### 支持的输出方式

- 中文完整版
- English Prompt
- ChatGPT-Image
- Midjourney
- Flux / SDXL
- 批量生成版
- JSON 结构化版
- 精简省 Token 版

### Skill 文件

完整规则、触发条件、执行逻辑和输出模板都在：

**[SKILL.md](./SKILL.md)**

---

## English

### What is this?

This repository contains an image-generation prompt Skill that converts character, outfit, accessory, and emotion descriptions into structured fashion-board prompts.

You provide:

- a shared character setup
- outfit descriptions
- shoes, socks, bags, and accessories
- matching emotions / facial expressions

The Skill converts them into complete prompts that can be used directly with image-generation models.

### Default Composition

- Top section: full-body front view, 90° side view, and back view
- Bottom section: matching facial-expression close-up
- Minimal white studio background
- Soft, even high-key lighting
- Realistic fabric and skin texture
- Fashion Lookbook / Character Sheet layout

### Good for

- outfit boards
- character turnarounds
- emotion boards
- character sheets
- fashion lookbooks
- batch prompt generation

### Usage

Provide a character setup followed by one or more outfit/emotion pairs:

```text
Shared character setup:
Young adult East Asian woman, long dark-brown wavy hair, white studio background, realistic photography.

1 | White camisole + denim shorts | Chin-up smug expression
[Outfit description]
[Expression description]

2 | Blue striped shirt + black skirt | Tearful expression
[Outfit description]
[Expression description]
```

The Skill separates each outfit and generates one complete three-view + emotion-close-up prompt for each look.

### Output Modes

- Chinese full prompt
- English prompt
- ChatGPT-Image
- Midjourney
- Flux / SDXL
- batch generation
- structured JSON
- compact token-saving format

### Skill File

See the full trigger rules, workflow, consistency rules, safety boundaries, and output templates here:

**[SKILL.md](./SKILL.md)**

---

## Repository Structure

```text
.
├── README.md   # Bilingual introduction / 中英文说明
└── SKILL.md    # Complete Skill definition / 完整 Skill 定义
```

## License

No license has been added yet. If you plan to share or redistribute this Skill, consider adding a license such as MIT.

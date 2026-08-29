---
name: three-view-emotion-outfit-board
description: Convert character, outfit, accessory, and emotion descriptions into consistent three-view fashion boards with matching facial-expression close-ups. 将人物、穿搭、配饰与情绪整理为统一的正面/侧面/背面三视图及对应表情近景。
version: 1.0.0
language:
  - zh-CN
  - en
---

# 01 — Three-View Emotion Outfit Board
# 01 — 三视图情绪穿搭图鉴生成器

[中文](#中文) | [English](#english)

---

## 中文

### 功能
把用户给出的统一人物设定、服装、鞋袜、包袋、配饰与情绪描述，整理成可直接用于图像生成的时尚图鉴提示词。

默认结构：
- 上半部分：Front 正面 / Side 90°侧面 / Back 背面完整全身三视图
- 下半部分：与该套穿搭对应的 Headshot 情绪面部近景
- 白色极简摄影棚背景
- 柔和均匀高调光线
- 真实皮肤与服装面料
- Fashion Lookbook / Character Sheet 排版

### 触发意图
当用户表达以下或相近意图时触发：
- 三视图穿搭图鉴
- 情绪穿搭图鉴
- 三视图 + 表情近景
- 把这些穿搭整理成生图提示词
- fashion lookbook sheet
- three-view emotion board
- character turnaround

### 执行逻辑
1. 提取并锁定统一人物身份、发型、身材、肤色、妆容、背景、光线与版式。
2. 将每套穿搭拆成独立任务，提取上装、下装/连衣裙、材质、颜色、鞋袜、包袋、配饰和情绪。
3. 为每套固定生成正面、90°侧面、背面与一张对应情绪近景。
4. 保证四个区域为同一人物、同一服装、同一发型、同一配饰，不发生颜色、长度、鞋型或身份漂移。
5. 把情绪转译为眉毛、眼睛、嘴型、头部角度与必要手势等可视化动作。
6. 多套穿搭逐套编号、逐套独立输出，不混合、不遗漏。

### 默认人物设定
若用户没有覆盖：
> 年轻成年东亚女性，纤细匀称身材，白皙自然肤色，小巧鹅蛋脸，黑棕色长卷发自然披肩，清透淡妆，真实皮肤纹理。白色极简摄影棚背景，柔和均匀高调光线，真实摄影质感，时尚穿搭图鉴排版。

### 固定一致性规则
- same character identity
- same hairstyle
- same natural body proportions
- same outfit and fabric
- same shoes / socks / bag / accessories
- full feet visible in all three full-body views
- no extra people
- no cluttered background
- no duplicated limbs
- no plastic skin
- no outfit drift

### 输出模板
```text
## LOOK X｜穿搭名称｜情绪名称

【统一人物设定】

画面采用时尚穿搭图鉴排版。上半部分横向排列 Front / Side / Back 三个完整全身视角；下半部分为对应情绪 Headshot。所有区域保持完全同一人物、同一发型、同一穿搭、同一鞋袜、同一包袋和同一配饰。

【服装与材质】
【鞋袜 / 包袋 / 配饰】
【Headshot 情绪与微表情】

真实摄影，真实皮肤纹理，真实服装面料，自然身体比例，画面整洁，像高质量 Fashion Lookbook / Character Sheet。
```

### 可选输出模式
- 中文完整版
- English Prompt
- ChatGPT-Image
- Midjourney
- Flux / SDXL
- 批量版
- JSON 结构化版
- 精简省 Token 版

### 安全边界
- 人物必须明确为成年人
- 保持正常时尚、人物设定与情绪写真范围
- 不生成露骨色情、违法、仇恨或图形化暴力内容

---

## English

### Purpose
Convert a shared adult character setup plus outfit, accessories, and emotion notes into production-ready image prompts for a consistent fashion reference board.

Default layout:
- Top: Front / 90° Side / Back full-body views
- Bottom: matching emotional Headshot
- Minimal white studio background
- Soft even high-key lighting
- Realistic skin and fabric texture
- Fashion Lookbook / Character Sheet presentation

### Trigger Intent
Use this Skill for requests such as:
- three-view outfit board
- emotion outfit board
- three-view + facial close-up
- fashion lookbook sheet
- character turnaround
- convert these outfits into image prompts

### Workflow
1. Lock the shared adult character identity, hairstyle, proportions, makeup, background, lighting, and layout.
2. Split every outfit into a separate task.
3. Extract garment type, material, color, shoes, socks, bag, accessories, and emotion.
4. Generate Front / Side / Back + one matching Headshot.
5. Preserve the exact same character and outfit across every panel.
6. Translate emotions into visible eyebrow, eye, mouth, head-angle, and gesture cues.
7. Output each outfit separately and never merge looks.

### Consistency Rules
Preserve the same character identity, natural body proportions, hairstyle, clothing, materials, footwear, bag, and accessories across every view. Keep feet visible. Avoid extra people, anatomy errors, duplicated limbs, outfit drift, plastic skin, and cluttered backgrounds.

### Safety
The character must be clearly adult. Keep outputs within normal fashion, character-design, and portrait boundaries.

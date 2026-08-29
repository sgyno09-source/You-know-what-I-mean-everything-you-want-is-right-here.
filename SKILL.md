---
name: three-view-emotion-outfit-board
description: Convert character, outfit, and emotion descriptions into consistent three-view fashion boards with matching facial-expression close-ups. 将人物、穿搭与情绪描述整理为统一的三视图穿搭图鉴与对应表情近景提示词。
version: 1.0.0
language:
  - zh-CN
  - en
---

# Three-View Emotion Outfit Board Generator
# 三视图情绪穿搭图鉴生成器

[中文](#中文) | [English](#english)

---

## 中文

### 1. Skill 功能

这个 Skill 用于把用户提供的**统一人物设定、穿搭描述、配饰信息和情绪表情描述**，自动整理成可直接用于图像生成模型的高质量提示词。

默认画面结构：

- 上半部分：全身正面、90°侧面、背面三视图
- 下半部分：与该套穿搭对应的情绪面部近景
- 白色极简摄影棚背景
- 柔和均匀的高调光线
- 真实服装面料与真实皮肤纹理
- 时尚穿搭图鉴 / Character Sheet / Lookbook 排版

适用于：

- 穿搭图鉴
- 人物三视图
- 情绪表情图鉴
- 角色设定板
- Fashion Lookbook
- Character Sheet
- 多套穿搭批量提示词

### 2. 触发条件

当用户表达以下任意意图时触发：

- 做成 Skill
- 三视图穿搭图鉴
- 情绪穿搭图鉴
- 穿搭三视图
- 三视图 + 表情近景
- 帮我整理成生图提示词
- 做成图鉴排版
- outfit board
- fashion lookbook sheet
- three-view emotion board
- character turnaround

只要用户的目标本质上是“**人物设定 + 穿搭 + 三视图 + 情绪近景**”，即使没有使用上述完全相同的关键词，也应执行本 Skill。

### 3. 核心目标

将自然语言描述转换为：

1. 结构完整
2. 可以直接生图
3. 人物身份稳定
4. 服装前后一致
5. 三视图关系明确
6. 表情与穿搭一一对应
7. 多套穿搭独立输出

### 4. 默认统一人物设定

如果用户没有另行指定，使用以下默认设定：

> 年轻成年东亚女性，纤细匀称身材，白皙自然肤色，小巧鹅蛋脸，黑棕色长卷发自然披肩，清透淡妆，保留真实皮肤纹理。白色极简摄影棚背景，柔和均匀高调光线，真实摄影质感，时尚穿搭图鉴排版。

如果用户已经提供人物设定，必须优先沿用用户设定，不要擅自改脸型、发型、肤色、年龄感或整体气质。

### 5. 固定构图规则

每套穿搭默认采用同一种画面结构：

**上半部分：**

1. 全身正面站姿
2. 全身 90° 侧面站姿
3. 全身背面站姿

**下半部分：**

- 对应该套穿搭的面部情绪近景
- 面部近景仍然保持同一人物
- 能看到与上半部分一致的领口、肩部或上装关键细节

三视图之间必须保持：

- 同一人物
- 同一发型
- 同一身材比例
- 同一套服装
- 同一鞋袜
- 同一包袋
- 同一配饰
- 同一面料与颜色

### 6. 执行逻辑

#### Step 1：提取全局设定

识别并锁定：

- 年龄感
- 人物类型 / 气质
- 脸型与五官风格
- 发型和发色
- 肤色
- 妆容
- 身材比例
- 背景
- 光线
- 摄影风格
- 排版类型

如果用户已经提供，严格沿用；没有提供的部分才使用默认值补齐。

#### Step 2：拆分穿搭组

每套穿搭作为一个独立输出单元，提取：

- 穿搭名称
- 上装
- 下装 / 连衣裙
- 材质
- 版型
- 颜色
- 包袋
- 鞋子
- 袜子
- 首饰 / 腰带 / 发饰等配饰
- 情绪名称
- 眉毛、眼睛、嘴巴、头部姿态、手部动作等表情细节

#### Step 3：处理服装一致性

将同一套服装分别映射到正面、侧面、背面和面部近景。

不要出现：

- 正面有包、背面包消失
- 正面长裙、侧面变短裙
- 鞋型发生变化
- 袜子颜色变化
- 衣服颜色漂移
- 近景换成另一套上衣
- 发型或人物身份变化

#### Step 4：处理情绪

情绪描述必须转化成可视觉化动作，优先描述：

1. 眉毛
2. 眼睛
3. 嘴型
4. 面部肌肉
5. 头部角度
6. 必要时加入手部动作

表情可以夸张，但默认保持真人摄影质感。

只有用户明确要求时，才加入漫画符号、蒸汽、怒气符号、速度线等二维元素。

#### Step 5：强化图像质量

提示词中默认强化：

- realistic skin texture
- realistic fabric texture
- natural body proportions
- consistent character identity
- consistent outfit details
- clean white studio background
- soft even high-key lighting
- premium fashion catalog layout
- clear full-body framing
- clean spacing
- realistic photography

避免：

- 多余人物
- 杂乱背景
- 无关道具
- 肢体畸变
- 五官漂移
- 服装漂移
- 重复肢体
- 截断脚部
- 三视图比例严重不一致
- 塑料皮肤
- 过度磨皮

#### Step 6：逐套独立输出

如果用户提供 2 套或更多穿搭：

- 每套单独编号
- 每套单独标题
- 每套单独完整提示词
- 不把不同穿搭合并进同一条提示词
- 不遗漏任何一套

### 7. 默认输出格式

```text
## 1｜穿搭名称｜情绪名称

年轻成年东亚女性，纤细匀称身材，白皙自然肤色，小巧鹅蛋脸，黑棕色长卷发自然披肩，清透淡妆，保留真实皮肤纹理。白色极简摄影棚背景，柔和均匀高调光线，真实摄影质感，时尚穿搭图鉴排版。

画面分区明确：上半部分为全身正面、90度侧面、背面三视图；下半部分为对应情绪的面部近景。三视图与近景中的服装、包袋、鞋袜、配饰保持完全一致，真实服装面料，清晰干净，像高质量时尚穿搭设定板。

【服装描述】

【包袋 / 鞋袜 / 配饰描述】

【对应情绪的面部近景描述】

整体效果时尚、统一、真实、清晰，兼具人物设定板与穿搭图鉴感。
```

### 8. 用户输入格式建议

用户无需严格按照模板输入，但下面格式最稳定：

```text
统一基础设定：
【人物、背景、光线、排版】

1｜穿搭名称｜情绪名称
【服装描述】
【表情描述】

2｜穿搭名称｜情绪名称
【服装描述】
【表情描述】
```

### 9. 内置示例穿搭

以下 8 组可作为测试样例或默认演示数据：

1. 白色不规则吊带 + 牛仔短裤｜傲到抬下巴撇嘴
2. 粉灰格纹衬衫 + 黑色短裤｜喜到咧嘴飞眉
3. 蓝白条纹衬衫 + 黑色短裙｜委屈到泪崩低头
4. 灰色针织开衫 + 牛仔短裙｜气到嘴巴变异
5. 黑色碎花方领长裙｜羞到脸红遮脸
6. 白色背心 + 米色不规则长裙｜疑到歪头挑眉
7. 浅粉色吊带蛋糕长裙｜怒到炸发瞪眼
8. 黑色碎花吊带长裙｜困到眯眼打哈欠

### 10. 可选输出模式

如果用户指定，可输出：

- 中文完整版
- English prompt
- ChatGPT-Image 版
- Midjourney 版
- Flux / SDXL 版
- 批量版
- JSON 结构化版
- 精简省 Token 版

如果用户没有指定模型，默认输出模型无关的自然语言提示词。

### 11. 安全边界

- 人物必须明确为成年人
- 默认保持正常时尚、人物设定与情绪写真范围
- 不生成露骨色情内容
- 不生成违法、仇恨或图形化暴力内容
- 对存在年龄歧义的人物，自动明确为成年角色

### 12. 最终执行指令

当本 Skill 被触发时：

1. 识别统一人物基础设定
2. 拆分所有穿搭与情绪组合
3. 保持人物身份稳定
4. 保持每套服装在三视图与近景中完全一致
5. 固定“正面 + 90°侧面 + 背面 + 情绪近景”结构
6. 强化服装面料、皮肤纹理和真实摄影感
7. 每套独立输出完整提示词
8. 用户要求批量时，不省略任何一套
9. 用户要求特定图像模型时，再针对模型调整语法
10. 除非用户要求解释，否则直接交付可用提示词

---

## English

### 1. Purpose

This Skill converts a user's **character setup, outfit description, accessories, and emotion/expression notes** into clean, production-ready prompts for image generation.

Default composition:

- Top: full-body front view, 90° side view, and back view
- Bottom: matching close-up facial expression
- Minimal white studio background
- Soft, even high-key lighting
- Realistic skin and clothing texture
- Fashion lookbook / character-sheet layout

Best used for:

- outfit boards
- character turnarounds
- emotion boards
- fashion lookbooks
- character sheets
- batch prompt generation

### 2. Trigger Intent

Activate this Skill for requests such as:

- make this into a Skill
- three-view outfit board
- emotion outfit board
- outfit turnaround
- three-view + facial close-up
- fashion lookbook sheet
- character turnaround
- convert these outfits into image prompts

The trigger is intent-based. Exact keyword matching is not required.

### 3. Core Goal

Convert natural-language input into prompts that are:

1. structurally complete
2. directly usable for image generation
3. identity-consistent
4. outfit-consistent
5. clear about all three views
6. paired with the correct facial emotion
7. separated one outfit per output

### 4. Default Character Setup

Unless the user overrides it:

> Young adult East Asian woman, slim and proportionate figure, fair natural skin tone, small oval face, dark brown long wavy hair worn down, light natural makeup, realistic skin texture. Minimal white studio background, soft even high-key lighting, realistic photography, clean fashion-board layout.

Always prioritize explicit user-provided character details over defaults.

### 5. Fixed Composition

For every outfit:

**Top section**

1. full-body front view
2. full-body 90-degree side view
3. full-body back view

**Bottom section**

- close-up portrait showing the specified emotion
- same character identity
- same hairstyle
- visible clothing details consistent with the top section

All views must preserve the same:

- character
- body proportions
- hairstyle
- outfit
- footwear
- socks
- bag
- accessories
- colors and fabrics

### 6. Workflow

#### Step 1 — Extract global character rules

Identify and lock:

- adult age impression
- character vibe
- facial style
- hairstyle and hair color
- skin tone
- makeup
- body proportions
- background
- lighting
- photographic style
- board layout

Use user-defined settings first. Fill only missing details with defaults.

#### Step 2 — Split outfit groups

Treat each outfit/emotion pair as one standalone output. Extract:

- outfit name
- top
- bottom or dress
- materials
- silhouette
- colors
- bag
- footwear
- socks
- accessories
- emotion name
- eyebrow, eye, mouth, head-angle, facial-muscle, and hand-action details

#### Step 3 — Preserve clothing consistency

Map the exact same clothing to front, side, back, and close-up views.

Never allow unexplained changes in:

- garment length
- bag presence
- shoe type
- sock color
- garment color
- neckline
- hairstyle
- character identity

#### Step 4 — Translate emotion into visible actions

Prioritize concrete facial cues:

1. eyebrows
2. eyes
3. mouth shape
4. facial tension
5. head angle
6. hand gestures when useful

Expressions may be exaggerated while remaining photorealistic.

Only add comic symbols or stylized effects when explicitly requested.

#### Step 5 — Reinforce quality

Default quality terms:

- realistic skin texture
- realistic fabric texture
- natural body proportions
- consistent character identity
- consistent outfit details
- clean white studio background
- soft even high-key lighting
- premium fashion catalog layout
- clear full-body framing
- clean spacing
- realistic photography

Avoid:

- extra people
- cluttered backgrounds
- unrelated props
- malformed anatomy
- identity drift
- outfit drift
- duplicated limbs
- cropped feet
- inconsistent view proportions
- plastic skin
- excessive retouching

#### Step 6 — Output separately

For multiple outfits:

- number every outfit
- give every outfit a clear title
- provide one complete prompt per outfit
- never merge different outfits into one prompt
- never omit an outfit

### 7. Default Output Template

```text
## 1 | Outfit Name | Emotion Name

Young adult East Asian woman, slim and proportionate figure, fair natural skin tone, small oval face, dark brown long wavy hair worn down, light natural makeup, realistic skin texture. Minimal white studio background, soft even high-key lighting, realistic fashion photography, clean outfit-board layout.

Clear split composition: the top section shows a full-body front view, 90-degree side view, and back view; the bottom section shows a matching facial close-up with the specified emotion. Outfit details, bag, shoes, socks, and accessories remain fully consistent across all sections.

[Outfit description]

[Bag / shoes / socks / accessories]

[Facial-expression close-up]

Overall result should feel stylish, clean, realistic, and cohesive, like a premium fashion emotion board and character sheet.
```

### 8. Optional Output Modes

When requested, adapt the output for:

- Chinese full prompt
- English prompt
- ChatGPT-Image
- Midjourney
- Flux / SDXL
- batch generation
- structured JSON
- compact token-saving format

If no model is specified, output model-agnostic natural-language prompts.

### 9. Safety

- Characters must be clearly adult
- Keep outputs within normal fashion, portrait, character-design, and emotion-board use
- No explicit sexual content
- No illegal, hateful, or graphic violent content
- Resolve age ambiguity by explicitly making the character an adult

### 10. Final Execution Rules

When triggered:

1. extract the shared character setup
2. split all outfit/emotion pairs
3. preserve character identity
4. preserve outfit consistency across all views
5. use the fixed front + side + back + emotion-close-up structure
6. emphasize realistic fabric, skin, and photography
7. output one complete prompt per outfit
8. never omit items in batch mode
9. adapt syntax only when a specific image model is requested
10. deliver usable prompts directly unless explanation is requested

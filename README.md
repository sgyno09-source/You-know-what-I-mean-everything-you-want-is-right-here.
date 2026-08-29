# You Know What I Mean — Skill Collection
# 你知道我意思的 — Skill 合集

[中文](#中文) | [English](#english)

> A growing collection of reusable image-generation and visual-workflow Skills.
>
> 一个持续整理的图像生成、人物设定与视觉工作流 Skill 仓库。

---

## 中文

### Skill 索引

#### 01｜三视图情绪穿搭图鉴生成器
**Three-View Emotion Outfit Board Generator**

把人物设定、服装、鞋袜、包袋、配饰与情绪描述，整理为统一的：

- Front 正面
- Side 90°侧面
- Back 背面
- Headshot 情绪近景

默认采用白色极简摄影棚、柔和高调光线与 Fashion Lookbook / Character Sheet 排版。

**适合：**
人物三视图、穿搭图鉴、角色设定板、表情图鉴、多套服装批量提示词。

➡️ **[打开 Skill 01](./skills/01-three-view-emotion-outfit-board/SKILL.md)**

---

#### 02｜镜面自拍穿搭情绪 Look Book 生成器
**Mirror Selfie Lookbook Emotion Board**

把室内全身镜自拍、多套都市穿搭和对应微表情，整理为统一的黑色杂志式 Look Book：

- Front 正面镜自拍
- Side 侧面镜自拍
- Back 背面镜自拍
- Headshot 完整面部情绪大头贴

固定低饱和黑灰室内环境、真实手机摄影、自然身体比例，并严格保持同一人物、同一发型、同一服装、同一鞋子与同一场景。

内置 8 套 Look：

1. 黑色吊带迷你裙｜委屈感
2. 白衬衫＋黑色皮裙｜无辜眼神
3. 黑色露肩娃娃裙｜期待
4. 白衬衫＋白色包臀长裙｜放松呼吸感
5. 灰蓝吊带＋白色迷你裙｜小得意
6. 咖啡色修身连体短裤｜慢半拍微笑
7. 裸粉上衣＋白色迷你裙｜欲言又止
8. 裸粉色 A 字短裙｜偷看镜头

**适合：**
都市穿搭 Look Book、镜面自拍参考板、角色衣橱设定、服装档案、情绪大头贴。

➡️ **[打开 Skill 02](./skills/02-mirror-selfie-lookbook-emotion-board/SKILL.md)**

---

### 仓库结构

```text
.
├── README.md
├── SKILL.md                         # Legacy / 原始兼容入口
└── skills/
    ├── 01-three-view-emotion-outfit-board/
    │   └── SKILL.md
    └── 02-mirror-selfie-lookbook-emotion-board/
        └── SKILL.md
```

后续新增 Skill 建议继续按：

```text
03-skill-name/
04-skill-name/
05-skill-name/
```

依次排列，方便长期扩展。

### 使用方法

打开对应 Skill 的 `SKILL.md`，将完整规则导入支持 Skill / Agent 指令的工作流即可。

每个 Skill 都包含：

- 功能说明
- 触发意图
- 执行逻辑
- 一致性规则
- 输出模板
- 中英文说明
- 安全边界

---

## English

### Skill Index

#### 01 | Three-View Emotion Outfit Board Generator

Turns character, outfit, footwear, bag, accessory, and emotion descriptions into a consistent fashion reference board with:

- Front view
- 90° Side view
- Back view
- Matching emotional Headshot

The default visual setup uses a minimal white studio, soft high-key lighting, realistic fabric and skin texture, and a Fashion Lookbook / Character Sheet layout.

**Best for:** character turnarounds, outfit boards, emotion boards, fashion reference sheets, and batch prompt generation.

➡️ **[Open Skill 01](./skills/01-three-view-emotion-outfit-board/SKILL.md)**

---

#### 02 | Mirror Selfie Lookbook Emotion Board

Turns indoor full-length mirror selfies, multiple urban outfits, and matching micro-expressions into a consistent black editorial Look Book with:

- Front mirror selfie
- Side mirror selfie
- Back mirror selfie
- Full-face emotional Headshot

It locks the same adult character identity, hairstyle, outfit, footwear, black smartphone, environment, lighting, and natural body proportions across all views.

Built-in preset looks:

1. Black camisole mini dress — vulnerable / hurt expression
2. White shirt + black leather mini skirt — innocent gaze
3. Black off-shoulder babydoll dress — anticipation
4. White shirt + cream pencil midi skirt — relaxed breathing
5. Gray-blue camisole + white mini skirt — subtle smug satisfaction
6. Coffee-brown fitted romper — delayed soft smile
7. Nude-pink top + white mini skirt — hesitant, about to speak
8. Nude-pink A-line mini dress — playful glance back

**Best for:** urban fashion Look Books, mirror-selfie reference boards, wardrobe character sheets, fashion archives, and expression studies.

➡️ **[Open Skill 02](./skills/02-mirror-selfie-lookbook-emotion-board/SKILL.md)**

---

### Repository Structure

```text
.
├── README.md
├── SKILL.md                         # Legacy compatibility entry
└── skills/
    ├── 01-three-view-emotion-outfit-board/
    │   └── SKILL.md
    └── 02-mirror-selfie-lookbook-emotion-board/
        └── SKILL.md
```

Future Skills can continue in numeric order:

```text
03-skill-name/
04-skill-name/
05-skill-name/
```

### Usage

Open the desired `SKILL.md` and import its complete instructions into a compatible Skill / Agent workflow.

Each Skill includes:

- purpose
- trigger intent
- workflow
- consistency rules
- output templates
- bilingual documentation
- safety boundaries

---

## Notes

The root `SKILL.md` is preserved as a legacy compatibility entry. New Skills are organized under `/skills/` in numeric order.

---
name: bilingual-wedding-lookbook-presets
description: Generate premium bilingual wedding-dress lookbook posters with one consistent clearly adult model, a four-panel Front/Side/Back/Headshot layout, bilingual wedding-dress titles and expression labels, and eight built-in bridal presets. 生成统一成年模特的高级双语婚纱图鉴，固定 Front/Side/Back/Headshot 四宫格、中英婚纱标题与表情标签，并内置 8 套婚纱预设。
version: 1.0.0
language:
  - zh-CN
  - en
---

# 07 — Bilingual Wedding Lookbook Presets
# 07 — 中英双语婚纱四宫格图鉴预设

[中文](#中文) | [English](#english)

---

## 中文

### 1. Skill 功能

这个 Skill 用于把**同一位明确成年的年轻亚洲女性、婚纱造型、婚纱材质、对应表情和中英文标题**整理成高级婚纱 Lookbook / Catalog / Character Sheet 提示词。

默认视觉系统：

- 白色极简摄影棚背景
- 高级柔和均匀影棚光
- 轻奢时尚杂志 / 婚纱产品目录风格
- 四宫格：正面 Front / 侧面 Side / 背面 Back / 大头贴 Headshot
- 顶部显示编号 + 中文婚纱名 + English Name
- 表情使用中英双语标注
- 蕾丝、薄纱、缎面、刺绣、珠饰、蝴蝶结、拖尾、头纱等材质细节清晰可见

### 2. 默认模特

除非用户另行指定，固定为：

> 同一位明确成年的年轻亚洲女性，可爱一点、略带混血感，五官精致柔和，白皙通透自然肤色，长发大波浪、大弧度松卷，自然蓬松，温柔气质，淡妆，真实细腻皮肤纹理，身材纤细匀称，站姿优雅。

所有视图必须保持：

- 同一人物身份
- 同一脸型与五官
- 同一发型与发色
- 同一肤色和妆容
- 同一婚纱结构
- 同一鞋履、头纱、手套、皇冠、发饰等配饰
- 自然手部结构与身体比例

### 3. 固定四宫格结构

整张画面固定为四宫格：

1. 正面 Front
2. 侧面 Side
3. 背面 Back
4. 大头贴 Headshot

前三格完整展示婚纱全身结构。

正面重点：领口、胸衣、腰线、裙摆整体轮廓。

侧面重点：鱼尾、A 字、蓬裙、开衩、前短后长等侧面结构。

背面重点：拖尾、头纱、背部结构、绑带、蕾丝、蝴蝶结或缎面细节。

Headshot 重点：完整脸部、对应表情、头纱 / 皇冠 / 发饰与肩颈婚纱细节。

### 4. 固定文字系统

顶部标题格式：

`X｜中文婚纱名 English Wedding Dress Name`

表情标签格式：

`XX 中文表情 English Expression`

分区标签：

- 正面 Front
- 侧面 Side
- 背面 Back
- 大头贴 Headshot

字体使用简洁高级无衬线，黑色或深灰色，保持清晰、不遮挡人物、不出现乱码。

### 5. 婚纱材质与质量规则

提示词默认强化：

- realistic bridal fabric texture
- fine lace embroidery
- translucent tulle
- satin sheen
- dimensional floral applique
- beadwork and crystal details
- realistic veil layers
- clean studio lighting
- premium bridal catalog layout
- natural body proportions
- elegant hand poses
- consistent dress construction

避免：

- 人物身份漂移
- 婚纱前后结构变化
- 拖尾、头纱、手套、皇冠随机消失
- 蕾丝纹理糊成一片
- 薄纱与身体错误融合
- 多余手指
- 手部畸形
- 腿部或腰部扭曲
- 脚部截断
- 四宫格比例严重不一致
- 标题乱码或重复
- 过度磨皮

### 6. 执行逻辑

#### Step 1 — 锁定人物
识别人物参考设定。用户有参考图时优先保持参考图身份；否则使用默认成年模特设定。

#### Step 2 — 锁定婚纱结构
提取婚纱的领口、肩部、胸衣、腰线、裙型、开衩、拖尾、材质、头纱、手套、皇冠、发饰和鞋履。

#### Step 3 — 分配四视图重点
Front / Side / Back 分别强调对应服装结构，Headshot 展示指定表情与头部配饰。

#### Step 4 — 保持一致性
同一套婚纱在四格中不得改变颜色、材质、长度、拖尾、头纱和主要装饰。

#### Step 5 — 输出
多套婚纱时，每套独立输出完整提示词，不混合不同婚纱。

---

## 7. 内置 8 套婚纱预设

### 1｜蕾丝鱼尾婚纱 / Lace Mermaid Wedding Dress

服装：白色无肩带蕾丝鱼尾婚纱，立体刺绣花纹，修身束腰剪裁，半透明蕾丝裙摆，拖地长尾，白色蕾丝长手套与轻薄头纱，优雅法式新娘风。

视图重点：正面展示整体轮廓；侧面展示鱼尾曲线；背面展示拖尾与头纱。

表情：`01 自然微笑 Natural Smile`。嘴角微微上扬，眼神温柔自然。

### 2｜蝴蝶结蛋糕婚纱 / Bow Cake Wedding Dress

服装：白色抹胸束腰婚纱，胸前超大蝴蝶结与立体玫瑰装饰，半透明束身马甲结构，多层蓬松薄纱蛋糕长裙，层层荷叶边，甜美公主风。

表情：`02 俏皮眨眼 Playful Wink`。单眼轻闭，嘴角带笑，头微微歪向一侧。

### 3｜开衩蕾丝鱼尾婚纱 / Slit Lace Mermaid Wedding Dress

服装：白色抹胸蕾丝婚纱，精致花卉刺绣，紧身收腰鱼尾剪裁，高开衩设计，轻薄纱质拖尾，长款头纱，珍珠皇冠，优雅时尚新娘造型。

表情：`03 灿烂大笑 Radiant Laugh`。自然露齿笑，眼睛弯起，明亮有感染力。

### 4｜缎面单肩鱼尾婚纱 / Satin One-Shoulder Mermaid Wedding Dress

服装：珍珠白缎面单肩婚纱，不对称褶皱领口，贴身收腰鱼尾剪裁，腰侧立体花卉装饰，简洁光泽缎面长裙，侧肩薄纱花饰，极简高级感。

表情：`04 坏笑／邪笑 Mischievous Smirk`。单边嘴角上扬，眼神略带得意与狡黠。

### 5｜蝴蝶花纹蓬裙婚纱 / Butterfly Pattern Ball Gown Wedding Dress

服装：白色细肩带婚纱，方形领口，满身立体蝴蝶结与花朵蕾丝刺绣，收腰 A 字蓬裙，半透明薄纱长裙，搭配短款头纱，清新甜美新娘风。

表情：`06 天真无邪 Innocent Sweetness`。眼睛明亮，神情干净单纯，嘴角自然上扬。

### 6｜复古宫廷婚纱 / Vintage Court Wedding Dress

服装：白色抹胸束身宫廷婚纱，胸口立体花朵装饰，宽大立体缎面蓬裙，高开衩结构，搭配黑色超长礼服手套与黑色蝴蝶结装饰，复古黑白高级时装感。

表情：`07 暗爽得意 Secretly Pleased`。单边嘴角轻扬，眼神半眯，带一点藏不住的得意。

### 7｜极简条纹纱裙婚纱 / Minimal Striped Tulle Wedding Dress

服装：象牙白无肩带婚纱，简洁抹胸上身，腰部半透明几何网格设计，A 字长裙，多层横向立体缎带条纹覆盖薄纱裙摆，极简现代新娘风。

表情：`08 宠溺笑 Adoring Smile`。嘴角温柔上扬，眼神柔软，像在看自己很喜欢的人。

### 8｜不规则短前长后婚纱 / High-Low Irregular Wedding Dress

服装：白色抹胸束身婚纱，银白立体刺绣与珠钻装饰，短前长后不规则薄纱裙摆，多层轻盈欧根纱结构，透明薄纱披肩袖与细钻发箍，轻盈仙气新娘风。

表情：`09 羞涩低头 Shy Downcast Smile`。嘴角抿着浅笑，眼神略微躲闪，头部微微低垂。

---

## 8. 默认输出模板

```text
白色极简摄影棚背景，高级婚纱图鉴 / Bridal Lookbook / Wedding Catalog 排版，柔和均匀影棚光，轻奢时尚杂志感，婚纱材质和细节清晰可见。

同一位明确成年的年轻亚洲女性，可爱一点、略带混血感，五官精致柔和，白皙自然肤色，长发大波浪、大弧度松卷，自然蓬松，淡妆，真实皮肤纹理，站姿优雅。

画面采用四宫格：正面 Front / 侧面 Side / 背面 Back / 大头贴 Headshot。前三格展示完整婚纱全身结构，第四格展示对应表情与头部配饰。四格保持完全同一人物、同一婚纱、同一头纱、同一鞋履与配饰。

顶部标题：【编号｜中文婚纱名 English Wedding Dress Name】
表情标签：【编号 中文表情 English Expression】

婚纱：【完整婚纱结构、材质、头纱、手套、皇冠、鞋履描述】
表情：【完整 Headshot 表情描述】

整体画面高级、通透、简洁规整，像高级婚纱品牌产品目录与时尚 Bridal Lookbook。
```

### 9. 可选输出模式

用户需要时可输出：

- 中文完整版
- English Prompt
- ChatGPT-Image 版
- Midjourney 版
- Flux / SDXL 版
- 8 套批量完整版
- 精简省 Token 版
- JSON 结构化版

### 10. 安全边界

- 人物必须明确为成年人
- 默认保持婚纱展示、时尚目录、正常人物写真范围
- 不生成露骨色情内容
- 不生成违法、仇恨或图形化暴力内容
- 遇到年龄歧义时自动明确为成年人物

---

## English

### 1. Purpose

This Skill generates premium bilingual bridal lookbook posters using one consistent clearly adult Asian female model.

Default system:

- minimal pure-white studio background
- soft even premium studio lighting
- four-panel Front / Side / Back / Headshot layout
- bilingual wedding-dress title and numbering
- bilingual expression label
- detailed rendering of lace, tulle, satin, embroidery, beadwork, bows, trains, gloves, crowns, and veils

### 2. Default Model

Unless overridden by the user:

> The same clearly adult young Asian woman with a cute slightly mixed-heritage look, refined soft facial features, fair natural skin, long voluminous loose waves, natural makeup, realistic skin texture, slim balanced proportions, and an elegant relaxed pose.

### 3. Fixed Layout

1. Front — full bridal silhouette and bodice
2. Side — side silhouette, mermaid curve, slit, volume, or high-low structure
3. Back — train, veil, back construction, bow, lace, or satin details
4. Headshot — full facial expression plus veil / crown / hair accessory details

### 4. Typography

Top title:

`X | Chinese Dress Name English Wedding Dress Name`

Expression:

`XX Chinese Expression English Expression`

Panel labels:

- 正面 Front
- 侧面 Side
- 背面 Back
- 大头贴 Headshot

### 5. Built-in Bridal Presets

1. Lace Mermaid Wedding Dress — Natural Smile
2. Bow Cake Wedding Dress — Playful Wink
3. Slit Lace Mermaid Wedding Dress — Radiant Laugh
4. Satin One-Shoulder Mermaid Wedding Dress — Mischievous Smirk
5. Butterfly Pattern Ball Gown Wedding Dress — Innocent Sweetness
6. Vintage Court Wedding Dress — Secretly Pleased
7. Minimal Striped Tulle Wedding Dress — Adoring Smile
8. High-Low Irregular Wedding Dress — Shy Downcast Smile

### 6. Consistency Rules

Keep the same adult model, face, hairstyle, makeup, wedding-dress construction, veil, gloves, crown, shoes, train, colors, fabrics, and accessories across all four panels.

Do not allow malformed hands, duplicated limbs, broken dress geometry, missing trains, disappearing veils, unreadable text, inconsistent silhouettes, plastic skin, or incorrect fabric blending.

### 7. Final Instruction

When triggered:

1. lock the adult model identity
2. identify the bridal outfit and all materials
3. map the outfit to Front / Side / Back / Headshot
4. preserve construction and accessories across all views
5. apply the requested expression to Headshot
6. use bilingual title and labels
7. output each bridal look separately
8. prioritize directly usable image-generation prompts

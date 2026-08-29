---
name: mirror-selfie-lookbook-emotion-board
description: Build consistent indoor mirror-selfie fashion lookbook prompts with Front/Side/Back views and a matching emotional Headshot for each outfit. 将室内全身镜自拍穿搭整理为统一的正面/侧面/背面 Look Book 与对应情绪大头贴。
version: 1.0.0
language:
  - zh-CN
  - en
---

# 02 — Mirror Selfie Lookbook Emotion Board
# 02 — 镜面自拍穿搭情绪 Look Book 生成器

[中文](#中文) | [English](#english)

---

## 中文

### 1. Skill 功能
这个 Skill 用于把用户提供的**统一人物设定、室内镜面自拍环境、穿搭描述和对应微表情**，整理成可直接用于图像生成模型的完整提示词。

默认画面结构：
- 顶部：显示 LOOK 编号与穿搭名称
- 上半部分：Front 正面 / Side 侧面 / Back 背面三个完整全身镜自拍视角
- 下半部分：一张横向 Headshot 大头贴，露出完整面部并表现指定微表情
- 整体为黑色杂志式 Look Book / Fashion Archive / Character Wardrobe Board 排版

### 2. 触发意图
当用户表达以下或相近意图时触发：
- 镜面自拍穿搭图鉴
- 黑灰 Look Book
- 三视图镜面自拍
- Front Side Back 自拍
- 穿搭 + 大头贴表情
- mirror selfie lookbook
- fashion archive board
- wardrobe character sheet
- outfit emotion board

只要用户目标本质上是“**同一成年人物 + 镜面自拍 + 多套穿搭 + 三个全身视角 + 情绪近景**”，即使没有使用完全相同的关键词，也应执行本 Skill。

### 3. 核心目标
将自然语言整理为：
1. 可直接用于生图的完整提示词
2. 同一人物身份稳定
3. 同一镜面自拍场景稳定
4. 每套服装在 Front / Side / Back 中完全一致
5. 手机、鞋子、发型和身体比例一致
6. Headshot 与每套服装、情绪一一对应
7. 多套 Look 独立输出、编号清晰

### 4. 默认统一人物设定
若用户没有另行覆盖，锁定为：

> 明确成年的年轻女性，纤细高挑、匀称自然的身材比例，腰线清晰，腿部修长但不过度夸张。长而浓密的深棕黑色自然波浪卷发，蓬松柔顺，部分碎发自然垂落脸侧，清透自然妆容，真实细腻皮肤质感。

### 5. 默认固定环境

> 室内全身镜自拍，背景固定为深灰黑色木质门板、灰色墙面与灰色瓷砖地面，低饱和黑灰空间，柔和室内侧光，轻微自然阴影，真实手机摄影质感，高级冷感都市氛围。

环境在不同 Look 之间默认保持完全一致，除非用户明确要求更换。

### 6. 固定 Look Book 排版
画面采用时装 Look Book 排版：

**顶部**
- LOOK 编号
- 中文穿搭名称
- 可附英文短标题

**上半部分**
1. Front：完整全身正面镜自拍
2. Side：完整全身侧面镜自拍
3. Back：完整全身背面镜自拍

三张必须保持：
- 同一人物
- 同一发型和发量
- 同一服装版型与长度
- 同一鞋子
- 同一手机
- 同一环境
- 同一光线
- 同一自然身体比例

人物手持黑色手机自拍。手机在全身视角中自然遮挡大部分面部；站姿放松，不夸张扭腰、翘胯或拉长腿部。

**下半部分**
- 横向 Headshot 大头贴
- 露出完整脸部，不再被手机遮挡
- 保持与上方完全同一人物
- 领口、发型、妆容等应与该套 Look 对应
- 精确执行该 Look 指定的微表情

### 7. 杂志视觉规则
默认强化：
- black editorial magazine layout
- minimal white sans-serif Chinese and English typography
- fashion archive presentation
- wardrobe reference board
- premium urban editorial feeling
- realistic mobile photography
- low-saturation charcoal-gray environment
- natural indoor side lighting
- realistic skin texture
- realistic garment fabric

不要生成：
- 多余人物
- 复杂装饰背景
- 夸张透视拉腿
- 不自然蜂腰或过度 S 曲线
- 三个视角服装漂移
- 手机颜色变化
- 鞋型变化
- 发型突然变短或变色
- Headshot 换脸
- 塑料皮肤
- 过度磨皮
- 多余文字堆叠

### 8. 情绪转译逻辑
Headshot 的情绪必须转成可视化微表情，优先按以下顺序描述：
1. 眉毛
2. 眼神与视线方向
3. 嘴角 / 嘴唇状态
4. 头部角度
5. 面部肌肉张力
6. 必要时加入轻微手势

默认保持真人、克制、自然，不把所有情绪做成夸张表情包。

### 9. 内置 Look 预设

#### LOOK 1｜黑色吊带迷你裙｜委屈感
服装：黑色细肩带修身迷你连衣裙，简洁方形领口，贴合胸腰与胯部，自然收腰，裙摆长度至大腿上部；黑色半透明连裤袜，黑色亮面尖头细高跟鞋。

风格：性感、克制、极简都市夜晚风格。

Headshot：眉头轻轻向中间皱起，眉尾略微下垂，湿润的眼睛直视镜头，嘴角轻微向下，嘴唇自然抿住，头部稍稍侧倾，像受了点委屈却忍住没有哭，脆弱、安静、惹人怜爱的神态。

#### LOOK 2｜白衬衫＋黑色皮裙｜无辜眼神
服装：宽松但具有自然垂坠感的白色长袖衬衫，翻领设计，领口自然打开两颗纽扣，袖口微松，衣摆塞入下装；黑色高腰亮面皮质包臀迷你裙，贴合腰臀曲线，简洁直筒剪裁；黑色半透明连裤袜，黑色亮面尖头细高跟鞋。

风格：轻熟、利落、办公室都市风。

Headshot：微微低头后抬眼看向镜头，眼睛清澈明亮，眉毛轻轻抬起，嘴唇自然微张，表情安静、单纯，带一点疑惑和无辜感。

#### LOOK 3｜黑色露肩娃娃裙｜期待
服装：黑色一字肩露肩娃娃迷你连衣裙，宽松荷叶式一字领，露出锁骨和肩部，长袖蓬松自然，胸部以下宽松下摆形成轻微 A 字廓形，裙长至大腿上部；黑色半透明连裤袜，黑色亮面尖头细高跟鞋。

风格：慵懒、甜酷、暗黑少女轻熟风。

Headshot：头部微微抬起并侧转，双眼望向侧上方，眼睛明亮，眉毛略抬，嘴唇轻轻张开，像正在等待一件好事发生，带一点憧憬、期待和好奇。

#### LOOK 4｜白衬衫＋白色包臀长裙｜放松呼吸感
服装：白色修身长袖衬衫，简洁翻领，衣摆完全塞入裙腰；奶油白色高腰修身包臀中长裙，贴合腰胯，笔直简洁剪裁，裙长至小腿中下部；裸色尖头细高跟鞋，裸腿。

风格：极简、优雅、成熟通勤风。

Headshot：闭上双眼，头部微微后仰，下巴自然抬起，嘴唇略微张开，肩颈完全放松，像正在缓慢深呼吸，安静、松弛、轻盈自然。

#### LOOK 5｜灰蓝吊带＋白色迷你裙｜小得意
服装：低饱和灰蓝色细肩带修身吊带上衣，简洁方领，贴合上半身；白色高腰修身包臀迷你裙，简洁无多余装饰，贴合腰臀，大腿上部长度；肩背与上衣颜色接近的灰蓝色小型腋下包；裸色尖头细高跟鞋，裸腿。

风格：干净、清冷、夏日都市轻熟风。

Headshot：眼睛微微眯起看向镜头，眉尾轻轻挑起，嘴角出现很浅的上扬笑意，头部稍微偏向一侧，像刚刚做成了一件值得得意的事情，带一点小傲娇和坏心思。

#### LOOK 6｜咖啡色修身连体短裤｜慢半拍微笑
服装：咖啡棕色无袖修身连体短裤，圆领或微高圆领设计，上半身贴合身形，腰部自然收紧，下半身为极简修身短裤，长度至大腿上部。面料柔软、有轻微弹性纹理，不夸张反光；裸腿，裸色尖头细高跟鞋。

风格：极简、成熟、慵懒的咖啡色都市穿搭。

Headshot：表情起初平静，眼神柔和看向镜头，嘴角像慢半拍一样才逐渐扬起形成浅浅微笑，眼神随之变温柔，像突然反应过来之后自然笑出来，不刻意营业。

#### LOOK 7｜裸粉上衣＋白色迷你裙｜欲言又止
服装：柔和裸粉色修身短袖上衣，简洁圆领，短款设计，贴合腰部和上半身；白色高腰修身包臀迷你裙，裙摆一侧带很小的侧开衩；裸腿，裸色尖头细高跟鞋。

风格：温柔、简洁、都市约会感。

Headshot：视线稍微偏向侧面，眼睛带一点犹豫，嘴唇轻微张开，一根手指轻轻触碰下唇附近，像本来想说些什么却临时停住，带一点迟疑、好奇和含蓄感。

#### LOOK 8｜裸粉色 A 字短裙｜偷看镜头
服装：柔和低饱和裸粉色无袖 A 字迷你连衣裙，较宽肩带，简洁方形领口，上半身自然修身，腰部明显收紧，下摆从腰线开始自然向外展开，形成轻盈 A 字裙摆，大腿上部长度；裸腿，裸色尖头细高跟鞋。

风格：温柔、甜美、干净的轻熟少女感。

Headshot：身体和肩部略微背向镜头，头部从肩膀方向轻轻转回来，眼睛偷偷看向镜头，嘴角带非常浅的小笑，像发现镜头后故意偷瞄一下，俏皮、灵动、有一点小心思。

### 10. 默认输出模板
```text
## LOOK X｜穿搭名称

明确成年的年轻女性，纤细高挑、匀称自然的身材比例，腰线清晰，腿部修长但不过度夸张。长而浓密的深棕黑色自然波浪卷发，蓬松柔顺，部分碎发自然垂落脸侧，清透自然妆容，真实细腻皮肤质感。

室内全身镜自拍，背景固定为深灰黑色木质门板、灰色墙面与灰色瓷砖地面，低饱和黑灰空间，柔和室内侧光，轻微自然阴影，真实手机摄影质感，高级冷感都市氛围。

画面采用黑色时装 Look Book 排版。顶部显示 LOOK X 与穿搭名称。上半部分横向排列 Front / Side / Back 三个完整全身镜自拍视角；三张保持完全同一人物、同一发型、同一服装、同一鞋子、同一黑色手机、同一环境与自然身体比例。手机自然遮挡大部分面部，站姿放松，不夸张扭腰扭胯。

【该套服装、材质、鞋子、包袋】

下半部分加入一张横向 Headshot 大头贴，露出完整脸部并保持同一人物身份。

Headshot 表情：【情绪名称】
【眉毛、眼睛、嘴唇、头部角度、必要手势的具体描述】

整体黑色杂志式设计，白色简洁无衬线中英文字体，真实时尚穿搭档案、服装参考板、角色设定集质感。真实手机摄影，真实皮肤与面料，自然比例，无额外人物，无服装漂移，无换脸。
```

### 11. 可选输出模式
用户指定时可输出：
- 中文完整版
- English Prompt
- ChatGPT-Image 版
- Midjourney 版
- Flux / SDXL 版
- 8 Look 批量版
- JSON 结构化版
- 精简省 Token 版

### 12. 安全边界
- 人物必须明确为成年人
- 保持正常时尚 Look Book、角色设定和肖像范围
- 不生成露骨色情内容
- 不生成违法、仇恨或图形化暴力内容
- 若年龄描述存在歧义，自动改为明确成年角色

### 13. 最终执行指令
当本 Skill 被触发时：
1. 锁定成年人物身份与固定镜面自拍环境
2. 拆分所有 Look 与对应微表情
3. 每套独立生成 Front / Side / Back + Headshot 结构
4. 三个全身视角中手机自然遮脸，Headshot 必须露出完整脸部
5. 保持人物、发型、服装、鞋子、包袋、环境、光线和身体比例完全一致
6. 微表情优先使用眉眼、嘴角、头部角度与轻微手势表达
7. 保持真实手机摄影和黑色编辑杂志质感
8. 用户要求批量时按 LOOK 1 → LOOK 2 → LOOK 3 的顺序依次输出
9. 用户指定图像模型时再调整对应语法
10. 除非用户要求解释，否则直接交付可用提示词

---

## English

### Purpose
This Skill converts a clearly adult character setup, a fixed indoor mirror-selfie environment, multiple outfits, and matching micro-expressions into consistent fashion Look Book prompts.

### Default Character
A clearly adult young woman with a slim, tall, naturally proportioned figure, defined waist, long legs without exaggerated stretching, long dense dark-brown/black naturally wavy hair, soft loose strands around the face, natural translucent makeup, and realistic skin texture.

### Fixed Environment
Indoor full-length mirror selfie in a low-saturation charcoal-gray interior with dark gray/black wooden door panels, gray wall, gray tiled floor, soft indoor side lighting, subtle natural shadows, realistic smartphone photography, and a cool premium urban mood.

### Fixed Layout
Top: LOOK number and outfit title.

Upper section: three full-body mirror-selfie panels arranged horizontally:
- Front
- Side
- Back

All three must preserve the exact same adult character, hairstyle, outfit, shoes, black smartphone, environment, lighting, and natural proportions. The phone naturally hides most of the face. Keep the pose relaxed and avoid exaggerated waist twisting, hip posing, or artificial leg elongation.

Lower section: one horizontal Headshot with the full face visible, matching the same character and outfit, showing the assigned micro-expression.

### Built-in Looks
1. Black camisole mini dress — hurt / vulnerable expression
2. White shirt + black leather mini skirt — innocent gaze
3. Black off-shoulder babydoll mini dress — anticipation
4. White shirt + cream pencil midi skirt — relaxed breathing
5. Gray-blue camisole + white mini skirt — subtle smug satisfaction
6. Coffee-brown fitted romper — delayed soft smile
7. Nude-pink top + white mini skirt — about-to-speak hesitation
8. Nude-pink A-line mini dress — playful glance back at camera

### Editorial Style
Use a black editorial magazine layout, minimal white sans-serif bilingual typography, fashion archive presentation, wardrobe reference-board aesthetics, realistic smartphone photography, realistic skin and garment texture, and a refined cool urban mood.

### Workflow
1. Lock the clearly adult character and fixed environment.
2. Split every LOOK into a separate output.
3. Preserve the same identity, hair, clothing, footwear, accessories, phone, proportions, and scene across Front / Side / Back.
4. Keep the phone hiding most of the face in full-body mirror-selfie panels.
5. Reveal the full face only in the Headshot.
6. Translate the requested emotion into subtle eyebrow, eye, mouth, head-angle, and gesture cues.
7. Output LOOKs sequentially in numeric order.

### Safety
The subject must be clearly adult. Keep outputs within normal fashion Look Book, character-reference, and portrait boundaries.

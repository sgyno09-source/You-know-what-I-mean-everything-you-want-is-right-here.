---
name: ultrawide-ui-street-ad-presets
description: Generate hyper-realistic 3:4 street-fashion advertising prompts that fuse a consistent reference person with forced-perspective photography, physicalized mobile UI, music cards, share sheets, call screens, maps, and surreal scale tricks. 生成 3:4 超写实街头广告视觉，将人物参考图与强制透视、实体化手机 UI、音乐卡片、分享界面、来电界面、地图与尺度错视融合。
version: 1.0.0
language:
  - zh-CN
  - en
---

# 05 — Ultrawide UI Street Ad Presets
# 05 — 超广角 UI × 真人街头广告视觉预设

[中文](#中文) | [English](#english)

---

## 中文

### 1. Skill 功能
这个 Skill 用于把用户提供的 `{{人物参考图}}`、`{{服装}}`、`{{街道/建筑}}`、`{{专辑封面}}`、`{{歌曲名}}`、`{{城市}}` 等变量，整理成超写实真人摄影与手机 UI / 玻璃界面 / 强制透视融合的创意广告提示词。

默认比例：**3:4 竖版**。

核心视觉特征：
- 超写实真人街拍 / 商业广告摄影
- 24–28mm 超广角与强制近大远小透视
- 真实皮肤、手部、服装织物、金属首饰和鞋履材质
- 手机 UI、音乐卡片、地图、分享面板等元素实体化为真实空间物体
- 人物与数字界面之间形成明显前后空间层级
- 高级街头时装杂志、手机广告、潮流创意大片质感

### 2. 触发意图
当用户表达以下或相近意图时触发：
- 超广角创意街拍
- UI 和真人融合
- 手机界面广告
- 音乐卡片悬浮
- 照片分享界面
- 人物从屏幕里出来
- 来电界面创意海报
- 大头小身体错视
- 地图 UI 实体化
- forced perspective fashion ad
- mobile UI fashion photography
- street advertising prompt

只要用户目标本质上是“**参考人物 + 真人摄影 + 强制透视 / UI 融合 / 空间错位**”，就应执行本 Skill。

### 3. 人物一致性规则
使用 `{{人物参考图}}` 时必须：
- 将参考图作为唯一人物身份来源
- 严格保持脸型、五官比例、发型、肤色、年龄感和整体辨识度
- 不随机换脸，不漂移发型，不改变人物性别或年龄
- 如画面包含同一人物的多张照片，只能是同一身份的不同姿势
- 人物必须明确为成年人

### 4. 通用摄影规则
除非某个模板明确覆盖，否则默认：
- 3:4 竖版
- 超写实真人摄影
- 24–28mm 广角
- 强制透视 / 近大远小
- 真实自然光或高级商业摄影光
- 高清皮肤纹理与服装织物
- 真实手部骨骼和五指结构
- 合理阴影、反射、厚度和遮挡关系
- UI 不作为平面贴纸，而是具有真实空间感

### 5. 通用负面约束
默认禁止：
- 多余手指、缺失手指、手指融合
- 手掌或肢体畸形
- 人物重复五官、身份漂移
- 手机 / 相机结构错误
- 卡片穿模、界面穿过身体
- UI 乱码、文本随机错乱
- 过度卡通化
- 低清晰度、塑料皮肤
- 错误透视、鞋子或腿部畸变
- 重复肢体

如果模型对精确 UI 文本能力较弱，优先保持**版式与层级正确**，并将文字限制为用户明确要求的短词。

---

## 6. 内置 7 套视觉预设

### 01｜悬浮音乐卡片手势街拍
**Floating Music Cards / Forced-Perspective Hand**

变量：
- `{{人物参考图}}`
- `{{街道/住宅门口/咖啡店外}}`
- `{{服装}}`
- `{{专辑封面}}`
- `{{歌曲名}}`
- `{{歌手名}}`

固定结构：
- 背景为低饱和灰蓝色复古大门或相近街头建筑
- 日间自然光，背景轻微虚化
- 人物居中，身体略后退
- 一只手极度靠近镜头，五指张开形成强烈超广角前景
- 手掌和手指占据明显前景，人物脸部位于后方
- 银色戒指和简约配饰突出手部造型
- 手部周围悬浮 4–5 张大型音乐播放器卡片
- 卡片为圆角半透明深灰玻璃材质，具有真实厚度、反光、阴影和不同空间角度
- 卡片大小不一，近处更大，远处更小，建立纵深

每张卡片可包含：
- `{{专辑封面}}`
- `{{歌曲名}}`
- `{{歌手名}}`
- 播放 / 暂停
- 上一首 / 下一首
- 进度条
- 无线播放图标

推荐摄影：28mm，强制透视，真实手机摄影，高级街头音乐广告。

### 02｜巨型照片分享 UI + 人物突破屏幕
**Photo Share Sheet / Person Breaking Out of UI**

变量：
- `{{人物参考图}}`
- `{{服装}}`
- `{{手机/相机/其他物品}}`

固定结构：
- 整个背景设计为巨大的手机照片分享界面
- 顶部保留：`1 Photo Selected`、`Options`、关闭按钮
- 中部为巨大照片预览区
- 底部为大型分享应用图标区
- 人物位于照片预览中央，并像剪纸抠图一样从照片界面真实走到 UI 前方
- 人物一只手伸向镜头，握住被极度夸大的 `{{手机/相机/其他物品}}`
- 物体极近镜头，手部 / 物体 / 人物身体形成清楚近大远小关系
- 照片预览区域可出现同一人物的其他街拍姿势，形成写真合集

底部可使用：
- AirDrop
- Messages
- Mail
- WhatsApp

整体白色系统 UI、圆角卡片、柔和阴影、极简界面，真人从 UI 中突破出来。

### 03｜三栏分享界面 + 坐姿突破边框
**Three-Column Share UI / Sitting Out of the Screen**

变量：
- `{{人物参考图}}`
- `{{服装}}`
- `{{帽子}}`
- `{{眼镜/首饰}}`
- `{{上衣}}`
- `{{裤子}}`
- `{{袜子}}`
- `{{鞋子}}`
- `{{配饰}}`

固定结构：
- 背景是放大的手机照片分享页面
- 白色极简系统 UI
- 顶部照片选择区域
- 中间三栏照片预览
- 底部大型分享应用图标
- 人物坐在中间照片预览框中的台阶上
- 躯干起始于照片区域，但真实身体突破照片边框延伸到 UI 前方
- 一条腿自然屈起，另一条腿向画面下方伸出
- 鞋子可以覆盖到底部分享图标区域，制造“从屏幕掉出来”的立体效果
- 人物低头整理帽檐，一只手插入口袋，姿态松弛
- 左右两侧保留同一人物局部照片，如背影、服装细节、手部戒指特写

摄影：真实织物纹理，真实鞋履，轻微鱼眼，杂志拼贴设计，清晰空间层级。

### 04｜胸前实体音乐播放器 + 有线耳机
**Wearable Music Player Card**

变量：
- `{{外套颜色与款式}}`
- `{{内搭}}`
- `{{裤子}}`
- `{{银色戒指/腕表/项链}}`
- `{{专辑封面}}`
- `{{歌曲名}}`
- `{{歌手名}}`
- `{{灰蓝色/黑色}}`

固定结构：
- 3:4 竖版
- 只拍肩膀至腰部，不完整露出脸部
- 可使用高饱和复古服装撞色
- 双手交叠于胸前 / 腹部，手指自然张开，重点展示首饰
- 白色有线耳机从颈部垂落，耳机线穿过双手
- 胸口前方悬浮一个约手机大小的实体化音乐播放器卡片
- 卡片可为透明玻璃或半透明彩色材质
- 播放器与耳机线建立视觉联系，像真正挂在人物胸前
- 具有真实厚度、反射、高光和阴影

播放器可包含：专辑封面、歌曲、歌手、播放暂停、上一首 / 下一首、进度条、无线播放图标。

背景使用低饱和建筑墙面，强调服装纹理和金属反光。

### 05｜包袋内部视角 + 巨型来电界面
**Inside-the-Bag POV / Incoming Call UI**

变量：
- `{{人物参考图}}`
- `{{包袋/布料/衣服开口}}`
- `{{服装}}`
- `{{帽子}}`
- `{{墨镜}}`
- `{{复古住宅大门/街道/商店门口}}`
- `{{主题小字}}`
- `{{主标题}}`

固定结构：
- 摄影机位于被人物双手拉开的包袋 / 布料 / 衣服开口内部
- 左右两侧大面积布料成为自然前景框架
- 人物站在中央，从开口向镜头看
- 双手分别拉住左右两侧，形成第一人称互动
- 嘴巴微张，神态惊讶、好奇、趣味
- 明亮夏日街头自然光
- 画面覆盖半透明手机来电 UI

UI 可包含：
- `{{主题小字}}`
- `{{主标题}}`
- Message
- Voicemail
- `slide to answer`

UI 为磨砂玻璃、白色文字、大号圆角滑动按钮，与真人画面融合。

### 06｜夸张大头小身体 + 巨手夹头错视
**Oversized Head / Giant Hands Optical Illusion**

变量：
- `{{人物参考图}}`
- `{{灰蓝色复古住宅门口/街道建筑前}}`
- `{{帽子}}`
- `{{眼镜}}`
- `{{外套}}`
- `{{内搭}}`
- `{{宽松长裤}}`
- `{{鞋子}}`

固定结构：
- 人物完整身体居中，身体保持正常偏小比例
- 双手插袋，站姿自然
- 头部夸张放大至正常约 2.5–3 倍
- 两只巨大前景手分别从左右两侧进入镜头
- 巨手托住 / 夹住人物头部两侧，手臂占据左右大面积前景
- 人物嘴唇微撅，搞怪、无奈、冷酷
- 效果必须仍然是超写实摄影，不转成卡通

摄影：24mm 超广角，高级杂志错视创意大片。

### 07｜第一人称脚下地图 UI 实体化
**First-Person Street Map Glass UI**

变量：
- `{{裤子}}`
- `{{袜子}}`
- `{{鞋子}}`
- `{{黄色道路标线/白色道路标线}}`
- `{{城市}}`
- `{{区域}}`
- `{{街道}}`
- `{{目的地}}`
- `{{头像/Memoji/卡通头像}}`

固定结构：
- 第一人称低头俯拍，模拟人物看向自己脚下
- 前景仅出现双腿和鞋子
- 真实粗糙柏油路面，带指定道路标线
- 侧向阳光制造明确真实阴影
- 脚下放置巨大圆角地图导航卡片
- 卡片像真实玻璃屏幕平铺或轻微悬浮于路面
- 地图显示浅色街区、灰色道路、餐厅 / 地标图标
- 中央为 `{{头像/Memoji/卡通头像}}` 与蓝色定位点
- 两侧可悬浮：搜索、3D、地图图层、导航定位等圆形按钮
- 地图卡片具有真实厚度、玻璃反射和落地阴影

摄影：傍晚金色阳光，第一人称旅行摄影，高级手机广告风。

---

## 7. 参数替换逻辑
当用户提供变量时：
1. 先锁定 `{{人物参考图}}` 与人物身份。
2. 再替换服装 / 配饰 / 场景。
3. 再替换 UI 内容、歌曲信息、城市 / 地图信息。
4. 不应擅自改动用户已经明确的品牌、歌曲名、地点名或服装。
5. 用户未提供的非关键变量可以用与视觉风格匹配的中性默认值补齐。
6. UI 文案尽量短，避免模型生成长段乱码文字。

### 8. 默认输出格式
用户选择某一模板时，输出：

```text
## 05-01｜悬浮音乐卡片手势街拍

【完整可直接生图提示词】

变量：
- 人物参考图：{{人物参考图}}
- 服装：{{服装}}
- 场景：{{场景}}
- 歌曲：{{歌曲名}}
...
```

如用户一次指定多个模板，则逐个编号独立输出，不混成一条。

### 9. 质量控制
特别强化：
- forced perspective
- correct hand anatomy
- five fingers per hand
- physically plausible glass UI
- realistic occlusion
- depth layering
- realistic reflections and shadows
- consistent character identity
- realistic fabric and jewelry texture
- commercial fashion photography

### 10. 安全边界
- 人物必须是成年人
- 保持正常时尚、广告、创意摄影范围
- 不生成色情、违法、仇恨或图形化暴力内容
- 不把 UI 设计成欺骗用户进行真实金融、账号或支付操作的钓鱼界面
- 如使用真实 App 风格，仅作为视觉概念，不伪造成真实可操作系统截图

### 11. 最终执行指令
当本 Skill 被触发时：
1. 判断用户最接近 01–07 中哪一种视觉模板。
2. 锁定人物参考图的身份一致性。
3. 提取并替换所有 `{{变量}}`。
4. 保留 3:4 竖版、超写实真人摄影、空间错位和高级广告感。
5. 对手部、腿部、手机、UI 卡片和透视关系写出明确约束。
6. 用户要求批量时，每个模板单独生成完整提示词。
7. 用户没有指定具体模板时，可根据目标推荐最适合的一种，但不要擅自混合全部模板。
8. 除非用户要求解释，否则直接交付可用提示词。

---

## English

### Purpose
This Skill creates hyper-realistic **3:4 vertical street-fashion advertising prompts** that combine a consistent reference person with forced-perspective photography and physicalized mobile UI.

It includes seven built-in visual systems:
1. Floating music-player cards around an extreme foreground hand
2. Giant photo share sheet with the person breaking out of the screen
3. Three-column share UI with a seated body extending beyond the photo frame
4. Wearable music-player card connected to wired earphones
5. Inside-the-bag POV with a translucent incoming-call interface
6. Oversized-head / tiny-body optical illusion with giant foreground hands
7. First-person street map rendered as a physical glass navigation panel

### Core Rules
- Use `{{人物参考图}}` as the only identity reference.
- Preserve face shape, facial features, hairstyle, skin tone, adult age impression, and recognizability.
- Default to 3:4 vertical framing.
- Use 24–28mm wide-angle perspective when appropriate.
- Treat UI cards as real objects with thickness, shadows, reflections, and occlusion.
- Preserve correct hand anatomy and realistic body proportions unless a preset intentionally changes scale.
- Keep interface text short and intentional.

### Replaceable Variables
Common placeholders include:
- `{{人物参考图}}`
- `{{服装}}`
- `{{街道/住宅门口/咖啡店外}}`
- `{{专辑封面}}`
- `{{歌曲名}}`
- `{{歌手名}}`
- `{{手机/相机/其他物品}}`
- `{{帽子}}`
- `{{眼镜/首饰}}`
- `{{城市}}`
- `{{区域}}`
- `{{街道}}`
- `{{目的地}}`

### Quality Constraints
Avoid extra fingers, fused hands, repeated limbs, broken phone geometry, duplicated faces, UI intersections, illegible clutter, low-resolution rendering, and incorrect depth ordering.

### Final Behavior
Identify the closest preset, substitute user variables, preserve strong forced perspective and commercial realism, then output one complete production-ready image prompt per requested preset.

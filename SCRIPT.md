# NAP Birthday Video - Case Study Showcase 30s
# Generated: 2026-04-16

## 项目概述
- 产品：NAP 定制皮克斯风生日视频
- 时长：30秒（2×15s clip）
- 风格：Pixar 3D卡通动画，高饱和度明亮童趣
- 价格：299 Australian Dollars
- 目标：案例展示为主，少口播

## 角色（沿用上一轮资产）
- Nick：棕发男孩，深绿T恤灰色短裤
- Koko：灰色考拉，银框眼镜，蓝色背带裤
- Roobin：红棕色成年袋鼠，蓝色棒球帽
- 资产路径：characters/char_nick.jpg | char_koko.jpg | char_roobin.jpg

## 5个案例
1. Emma - 5岁 - 水下美人鱼主题生日派对（Underwater Mermaid）
2. Liam - 8岁 - 太空探险主题生日（Space Explorer）
3. Sofia - 6岁 - 公主城堡主题生日（Princess Castle）
4. Oscar - 7岁 - 恐龙探险主题生日（Dinosaur Adventure）
5. Lucy - 4岁 - 丛林冒险主题生日（Jungle Adventure）

---

## CLIP A (0-15s) - 案例展示 PART 1

**场景路径：**
- scene 1: scenes/case_emma_underwater.jpg
- scene 2: scenes/case_liam_space.jpg
- scene 3: scenes/case_sofia_castle.jpg

**分镜：**
- 0-3s：开场 — 多元宇宙生日场景快闪蒙太奇
  口播："Sometimes the best birthdays happen ANYWHERE."
- 3-6s：案例1 Emma - 水下美人鱼主题
  口播："Emma turned 5 in an underwater kingdom!"
- 6-9s：案例2 Liam - 太空主题
  口播："Liam's 8th birthday was out of this world!"
- 9-12s：案例3 Sofia - 公主城堡主题
  口播："Sofia celebrated in a magical princess castle!"
- 12-15s：过渡
  口播："But that's not all..."

---

## CLIP B (15-30s) - 案例展示 PART 2 + CTA

**场景路径：**
- scene 4: scenes/case_oscar_dinosaur.jpg
- scene 5: scenes/case_lucy_jungle.jpg
- scene 6: scenes/product_showcase.jpg

**分镜：**
- 0-5s：案例4 Oscar - 恐龙主题
  口播："Oscar's 7th birthday was a prehistoric adventure!"
- 5-8s：案例5 Lucy - 丛林探险主题
  口播："Little Lucy explored the wild jungle!"
- 8-12s：产品展示 — 场景切换盘 + 价格
  口播："You can do ANY of this — starting from just 299 Australian Dollars!"
- 12-15s：CTA
  口播："Send us ONE photo. We'll create the whole world. Order now!"

---

## 制作 SOP
1. 用 Dreamina text2image 生成 5 个案例场景图（scenes/）
2. 用上一轮的角色图（characters/）作为角色资产
3. 提交 Clip A（multimodal2video，引用 scene 1+2+3 + characters）
4. 等待 Clip A 完成
5. 裁剪 Clip A 最后一帧
6. 提交 Clip B（multimodal2video，引用 A.mp4 最后一帧 + scene 4+5+6 + characters）
7. 等待 Clip B 完成
8. 合并 A+B → 30s 最终视频
9. 配音（可选 hailuo 或本地 TTS）

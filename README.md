# ai-picture-book-for-baby
AI-powered personalized picture book skill for OpenClaw. Create unique storybooks for babies using real-life photos and details.为宝宝创作专属AI绘本的OpenClaw Skill，融入真实生活细节，让每本绘本都独一无二。
📚 AI 专属绘本制作师
为宝宝创作独一无二的个性化绘本，从故事构思到画面描述，全流程陪伴。
---
✨ 能做什么
输入宝宝的真实信息（外貌、喜好、家里的物品），输出一套可直接用于 AI 绘画工具的绘本方案：
📖 故事脚本 — 适龄、有韵律、融入真实生活
🎨 画面描述词 — 固定画风 + 逐页画面，即梦/可灵直接可用
⚠️ 避坑指南 — 尺寸、人物一致性、背景保护
🖨️ 印刷建议 — 材质、装订、成本
---
🚀 快速开始
前提条件
安装 OpenClaw
有 AI 绘画工具账号（如即梦、可灵等）
准备好宝宝的照片和家里物品照片
安装
```bash
# 克隆到本地
git clone https://github.com/YOUR_USERNAME/picture-book-maker.git

# 将 SKILL.md 复制到你的 OpenClaw agent 工作空间
mkdir -p ~/.openclaw/workspace/agents/YOUR_AGENT_NAME/skills/picture-book-maker
cp picture-book-maker/SKILL.md ~/.openclaw/workspace/agents/YOUR_AGENT_NAME/skills/picture-book-maker/
```
使用
在 OpenClaw 对话中输入：
```
我想给我家宝宝做一本专属绘本
```
Agent 会引导你逐步提供信息，最终输出完整方案。
---
📖 输出示例
故事脚本
```
第1页 | 天黑了，小毛豆眨眨眼睛。红色小兔子说："今晚要自己睡觉哦。"
第2页 | 咕噜咕噜，喝完最后一瓶奶。小肚子鼓鼓的，真满足。
```
画面描述词
```
儿童绘本插画，温馨水彩风格，粗黑轮廓线，柔和粉彩色调，
简单背景，可爱Q版比例，圆滚滚造型，温暖治愈氛围，
300DPI高清，适合印刷，尺寸宽15x长30cm

1岁亚洲男宝宝坐在床上，宝宝特征参考上传的图片，
圆脸胖嘟嘟，短发有点炸毛，穿着浅蓝色小睡衣...
```
---
🎯 核心特点
特点	说明
真实物品融入	把家里的餐椅、玩偶、宠物画进绘本，专属感拉满
人物一致性	每页锚定同一张宝宝照片，角色不会变脸
适龄设计	1岁20-40字/页，拟声词+韵律，符合认知规律
避坑内置	尺寸、肤色、背景保护，不用踩雷
---
📋 制作流程
```
1. 收集宝宝信息（外貌、喜好、家庭物品）
2. 生成故事脚本（文字 + 场景）
3. 生成画面描述词（固定画风 + 逐页画面）
4. 避坑指南 + 印刷建议
```
详细流程见 SKILL.md
---
🖼️ 真实案例
《小毛豆的睡觉大冒险》 — 第一次自己睡觉
《第一次自己吃饭》 — 成长里程碑系列
---
⚠️ 注意事项
本 Skill 不直接生成图片，需配合 AI 绘画工具使用
建议使用 300DPI 高清参数，确保印刷质量
不要在 AI 绘画工具中直接添加文字，后期用 Canva 叠加保护背景
---
🤝 贡献
欢迎提交 Issue 和 PR：
分享你的绘本制作经验
补充更多年龄段的故事模板
优化画面描述词结构
---
📄 License
MIT License — 自由使用、修改、分享。
---
Made with ❤️ by 一位给娃做绘本的老母亲

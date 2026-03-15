<div align="center">

<!-- 语言切换 -->
<p>
  <a href="README.md">
    <img src="https://img.shields.io/badge/Language-English-blue?style=for-the-badge&logo=google-translate&logoColor=white" alt="English">
  </a>
  <a href="README_CN.md">
    <img src="https://img.shields.io/badge/Language-中文-red?style=for-the-badge&logo=google-translate&logoColor=white" alt="中文">
  </a>
</p>

<!-- 动态标题 -->
<img src="https://readme-typing-svg.herokuapp.com?font=Noto+Sans+SC&weight=600&size=45&duration=3000&pause=1000&color=6839E8&center=true&vCenter=true&width=800&lines=🏸+羽毛球极速计分板;专业+%C2%B7+高级+%C2%B7+极速+%C2%B7+免费" alt="Typing SVG" />

<h3>🚀 为羽毛球爱好者打造的殿堂级计分与管理系统</h3>

<p align="center">
  <img src="https://img.shields.io/badge/版本-2.5-6839E8?style=for-the-badge&logo=semver&logoColor=white" alt="Version">
  <img src="https://img.shields.io/badge/许可证-MIT-27F05C?style=for-the-badge&logo=opensourceinitiative&logoColor=white" alt="License">
  <img src="https://img.shields.io/badge/适配-全平台-00D9FF?style=for-the-badge&logo=skype&logoColor=white" alt="Platform">
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/1822520752/badmintonrapidscoreboard?style=social" alt="Stars">
  <img src="https://img.shields.io/github/forks/1822520752/badmintonrapidscoreboard?style=social" alt="Forks">
  <img src="https://img.shields.io/github/last-commit/1822520752/badmintonrapidscoreboard?color=00CEC9" alt="Last Commit">
</p>

---

[🌐 在线演示](https://1822520752.github.io/badmintonrapidscoreboard/) | [✨ 功能特性](#-功能特性) | [🚀 快速开始](#-快速开始) | [❓ 常见问题](#-常见问题)

</div>

## 🌟 为什么它与众不同？

本项目不只是一个简单的计分板，它是一个完整的羽毛球活动生态管理系统。

<table>
<tr>
<td width="33%">

### 💎 极致美学
**Glassmorphism 2.0**  
采用最前沿的磨砂玻璃设计语言，配合 Teko 科技感字体，每一像素都经过精心雕琢。

</td>
<td width="33%">

### 📱 触控先锋
**移动优先布局**  
专为手机端优化的全宽按钮与悬浮导航，单手即可完成所有复杂操作。

</td>
<td width="33%">

### 📊 深度洞察
**数据驱动分析**  
集成 Chart.js，不仅记录比分，更通过能力雷达图和胜率趋势深度剖析你的球技。

</td>
</tr>
<tr>
<td width="33%">

### 👥 智能调度
**公平分组算法**  
支持随机、实力平衡、轮换等多种模式，告别“固定搭档”的尴尬。

</td>
<td width="33%">

### 💰 账单大师
**一键费用分摊**  
内置 AA 制计算器，支持场地、球费、饮水等分类计算，生成美观账单分享。

</td>
<td width="33%">

### 🔐 零风险隐私
**100% 离线运行**  
数据仅存储在您的浏览器 LocalStorage 中，永不上传服务器，保护您的隐私。

</td>
</tr>
</table>

---

## ✨ 核心功能

### 🏸 专业计分系统
- **实时计时**：精确记录每一场比赛的耗时。
- **撤销机制**：支持无限次撤销，防止比分误触。
- **自动判定**：自动处理加分赛（Deuce）至30分封顶，符合国际羽联规则。
- **胜利动效**：华丽的胜利全屏特效与成就解锁提示。

### 👥 智能分组与费用管理
- **多种模式**：随机分组、实力均衡（强弱搭配）、循环赛制。
- **费用计算**：支持设置总额、人头分摊、自定义比例，一键复制结果。

### 📊 个人能力画像
- **雷达图分析**：全方位展示选手的体能、技术、防守、心态等维度。
- **排行榜**：基于胜率、场次、时长的多维度实时排名。
- **成就系统**：12个精心设计的勋章，记录你从“初次登场”到“羽坛王者”的进阶。

---

## 🎨 视觉主题

提供 6 种经过专业色彩调校的主题，满足不同光线环境下的使用需求：

- 💜 **暗夜紫**：深邃神秘，最具科技感。
- 🧡 **活力橙**：激发斗志，适合激烈对抗。
- 💙 **天空蓝**：清新自然，阅读体验极佳。
- 💚 **森林绿**：柔和护眼，缓解长时间盯盘疲劳。
- 💗 **樱花粉**：优雅细腻，深受女性玩家喜爱。
- 🖤 **黑金商务**：尊贵典雅，彰显专业品质。

---

## 🚀 快速开始

### 方案 A：即开即用（推荐）⭐
点击 [在线演示](https://1822520752.github.io/badmintonrapidscoreboard/) 链接，直接在浏览器中开始你的第一场比赛。

### 方案 B：本地部署
```bash
# 克隆项目
git clone https://github.com/1822520752/badmintonrapidscoreboard.git

# 进入目录
cd badmintonrapidscoreboard

# 使用 Python 启动（推荐，可获得最佳 PWA 体验）
python -m http.server 8000
```

---

## 🛠️ 技术底座

本项目坚持 **"Vanilla First"** 原则，以最轻量的体积实现最强大的功能：

- **核心**：HTML5, CSS3 (Modern Flex & Grid), ES6+ JavaScript
- **图表**：[Chart.js](https://www.chartjs.org/) - 强大的数据可视化
- **渲染**：[html2canvas](https://html2canvas.hertzen.com/) - 生成精美的分享卡片
- **存储**：LocalStorage & SessionStorage

---

## 🤝 参与贡献

我们非常欢迎开发者参与到项目中来！

1. **Fork** 本仓库
2. **Create** 你的功能分支 (`git checkout -b feature/AmazingFeature`)
3. **Commit** 你的修改 (`git commit -m 'Add some AmazingFeature'`)
4. **Push** 分支 (`git push origin feature/AmazingFeature`)
5. **Open** 一个 Pull Request

---

## 📄 许可证

本项目采用 [MIT 许可证](LICENSE) 授权。您可以自由使用、修改和分发。

---

<div align="center">

### 👨‍💻 作者
**TryWorld**  
热爱编程，热爱羽毛球 🏸

[![GitHub](https://img.shields.io/badge/GitHub-1822520752-181717?style=for-the-badge&logo=github)](https://github.com/1822520752)

**如果这个项目对你有帮助，请点一个 ⭐ Star 支持一下！**

<img src="https://api.star-history.com/svg?repos=1822520752/badmintonrapidscoreboard&type=Date" alt="Star History Chart" width="600">

</div>
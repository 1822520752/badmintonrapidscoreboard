# 🏸 羽毛球极速计分板

<div align="center">

**专业、简洁、极速的羽毛球比赛计分工具**

[![GitHub stars](https://img.shields.io/github/stars/1822520752/badmintonrapidscoreboard?style=for-the-badge)](https://github.com/1822520752/badmintonrapidscoreboard/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/1822520752/badmintonrapidscoreboard?style=for-the-badge)](https://github.com/1822520752/badmintonrapidscoreboard/network)
[![GitHub license](https://img.shields.io/github/license/1822520752/badmintonrapidscoreboard?style=for-the-badge)](https://github.com/1822520752/badmintonrapidscoreboard/blob/main/LICENSE)

[在线体验](#) · [功能特性](#功能特性) · [快速开始](#快速开始) · [技术栈](#技术栈)

</div>

---

## 📖 项目简介

羽毛球极速计分板是一款专为羽毛球爱好者设计的**免费、开源**计分工具。无论是日常练习、俱乐部活动还是正式比赛，都能提供流畅、专业的计分体验。

### 🎯 设计理念

- **极速操作** - 一键加分，无需复杂操作
- **数据驱动** - 自动记录历史，生成统计分析
- **视觉愉悦** - 精美UI设计，胜利动画庆祝
- **移动优先** - 完美适配手机和平板

---

## ✨ 功能特性

### 🏆 核心功能

| 功能 | 描述 |
|------|------|
| **快速计分** | 点击大圆圈或按钮即可加分，支持撤销操作 |
| **智能分组** | 输入选手名单，自动生成公平的对战分组 |
| **费用分摊** | 支持AA制、按人头、自定义比例分摊费用 |
| **历史记录** | 自动保存比赛数据，随时查看历史战绩 |
| **排行榜** | 胜场、胜率、参赛数、时长多维度排名 |
| **能力分析** | 基于真实数据计算选手能力值和成就标签 |
| **成就系统** | 12个成就等你解锁，增加运动乐趣 |

### 🎨 视觉体验

- **6套主题** - 暗夜紫、活力橙、天空蓝、森林绿、樱花粉、黑金商务
- **庆祝动画** - 获胜时彩带飘落、烟花绽放
- **分享卡片** - 一键生成精美比赛结果卡片
- **流畅动画** - 页面切换、按钮交互丝滑顺畅

### 📱 移动端优化

- 响应式设计，完美适配各种屏幕尺寸
- 双击屏幕快速呼出快捷操作面板
- 触摸友好的大按钮设计
- 隐藏滚动条，界面更整洁

---

## 🚀 快速开始

### 在线使用

直接打开 `index.html` 文件即可使用，无需安装任何依赖。

### 本地运行

```bash
# 克隆仓库
git clone https://github.com/1822520752/badmintonrapidscoreboard.git

# 进入目录
cd badmintonrapidscoreboard

# 启动本地服务器（可选）
python -m http.server 8000

# 浏览器访问
# http://localhost:8000
```

---

## 🛠️ 技术栈

| 技术 | 用途 |
|------|------|
| HTML5 | 页面结构 |
| CSS3 | 样式设计、动画效果 |
| JavaScript | 交互逻辑、数据处理 |
| Chart.js | 数据可视化图表 |
| LocalStorage | 本地数据持久化 |

---

## 📊 项目结构

```
badmintonrapidscoreboard/
├── index.html          # 主页面（包含所有代码）
├── README.md           # 项目说明
└── 仓库信息            # 仓库配置信息
```

---

## 🎮 使用指南

### 计分板

1. 点击"开始比赛"按钮启动计时
2. 点击大圆圈或"+"按钮为对应队伍加分
3. 点击"-"按钮可撤销误操作
4. 达到目标分数时自动判定本局胜负
5. 三局两胜制下，先赢两局者获胜

### 智能分组

1. 输入所有参赛选手名单（每行一个）
2. 选择分组模式（双打/单打）
3. 点击"开始分组"自动生成对战组合
4. 支持重新分组和保存结果

### 费用计算

1. 输入总费用金额
2. 选择分摊模式（AA制/按人头/自定义）
3. 自动计算每人应付金额
4. 支持添加额外费用项

---

## 🏅 成就系统

| 成就 | 条件 |
|------|------|
| 🏸 初次登场 | 完成第一场比赛 |
| 🎯 小有成就 | 完成10场比赛 |
| 🏆 球场老将 | 完成50场比赛 |
| 🎉 首胜 | 赢得第一场比赛 |
| 🥈 常胜将军 | 赢得10场比赛 |
| 🥇 羽坛王者 | 赢得25场比赛 |
| 🔥 三连胜 | 连续赢得3场比赛 |
| 💥 五连胜 | 连续赢得5场比赛 |
| ⏱️ 球痴 | 累计打球1小时 |
| ⌛ 球瘾 | 累计打球5小时 |
| ✨ 完美胜利 | 一局比赛零封对手 |
| 🎮 加分赛专家 | 经历3次加分赛 |

---

## 📝 更新日志

### v2.0
- ✨ 全新UI设计，视觉体验升级
- 🎨 新增6套主题切换
- 📊 新增数据可视化图表
- 🏆 新增排行榜系统
- 📈 新增选手能力分析
- 🎉 新增成就系统
- 🚀 新增新手引导
- ⚡ 新增快捷操作面板
- 📱 全面优化移动端体验

---

## 🤝 贡献指南

欢迎提交 Issue 和 Pull Request！

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 提交 Pull Request

---

## 📄 许可证

本项目采用 MIT 许可证 - 详见 [LICENSE](LICENSE) 文件

---

## 👨‍💻 作者

**试界 TryWorld**

- GitHub: [@1822520752](https://github.com/1822520752)

---

<div align="center">

**如果这个项目对你有帮助，请给一个 ⭐ Star 支持一下！**

Made with ❤️ by 试界 TryWorld

</div>

# 小熊猫闯迷宫 🐼🎮

一个用纯 HTML5 + JavaScript 开发的追逐类迷宫游戏！
那时候电脑课特别少，还总被数学和英语老师占用，电脑老师也不反抗争取。好不容易进机房，最喜欢玩的就是「警察抓小偷」——打字慢了就被抓，紧张得手心冒汗。但那时候就想：要是能用方向键跑，而不是敲键盘，该多爽啊！

现在学了计算机还略懂开发啦，哈哈哈~叛逆一下，做个纯方向键玩的追逐游戏把~~

## 🌐 在线试玩（推荐）

**🕹️ 立即开玩：https://zgdfsgd.github.io/panda-maze-game/**

无需下载，打开浏览器就能玩！

## 📦 项目仓库

**GitHub：https://github.com/Zgdfsgd/panda-maze-game**

---

## 🎮 游戏特色

- 🐼 **可爱小熊猫** —— 圆脑袋、黑眼圈，走路会摇摇晃晃
- 🐺 **恶狼追逐** —— 3 秒安全期，之后从起点开始追你
- 🎯 **15 个关卡** —— 从简单到复杂，难度递增
- ⚡ **紧张刺激** —— 被狼抓到要重新开始
- 🎉 **胜利特效** —— 通关有撒花庆祝动画
- 📱 **跨平台** —— PC 端键盘操作 / 手机端虚拟按键

## 🕹️ 游戏玩法

### 控制方式
- **电脑**：方向键 ↑↓←→ 或 WASD 控制移动
- **手机**：点击屏幕下方的虚拟方向键

### 游戏规则
1. 游戏开始后有 **3 秒安全期**，恶狼还没出来
2. 3 秒后恶狼从起点出发，用 BFS 最短路径追你
3. 找到 **金色出口** 即可通关
4. 如果被恶狼抓到，重新开始本关

### 通关技巧
- 恶狼速度约为你的 45%，正常走法肯定能通关
- 尽量走最短路径，不要绕远路
- 利用 3 秒安全期先规划路线

## 🛠️ 技术实现

- **纯原生代码**：HTML5 + CSS + JavaScript，无任何外部依赖
- **Canvas 2D 渲染**：流畅 60fps 动画
- **BFS 路径追踪**：恶狼使用广度优先搜索算法
- **Web Audio API**：动态音效
- **响应式设计**：适配电脑和手机

## 📁 文件结构

```
panda-maze-game/
├── index.html          # 完整游戏（单文件，由 panda-maze-game.html 重命名）
└── README.md           # 说明文档
```

## 🚀 本地运行

1. 克隆仓库：
```bash
git clone https://github.com/Zgdfsgd/panda-maze-game.git
```

2. 用浏览器打开 `index.html`

3. 开始游戏！

## 🎨 游戏截图

### 开始界面
![开始界面](https://zgdfsgd.github.io/panda-maze-game/screenshots/start.png)

### 游戏进行中
![游戏界面](https://zgdfsgd.github.io/panda-maze-game/screenshots/gameplay.png)

### 通关庆祝
![通关庆祝](https://zgdfsgd.github.io/panda-maze-game/screenshots/victory.png)

## 📝 开发记录

- **版本**：v2.0
- **更新时间**：2026 年 6 月 1 日
- **开发工具**：TRAE AI
- **游戏引擎**：纯 JavaScript + HTML5 Canvas
- **部署平台**：GitHub Pages

## 🗺️ 后续计划

- [ ] 增加更多关卡（目标 30 关）
- [ ] 添加道具系统（加速、隐身、陷阱）
- [ ] 支持双人模式（PVP 对战）
- [ ] 移动端触摸优化
- [ ] 添加音效和背景音乐
- [ ] 排行榜系统

## 🐛 反馈与建议

如果发现 bug 或有任何建议，欢迎：
- 提交 [Issue](https://github.com/Zgdfsgd/panda-maze-game/issues)
- 联系开发者：Zgdfsgd

## 📄 许可证

MIT License

---

## 🔗 快速链接

| 类型 | 链接 |
|------|------|
| 🎮 在线游戏 | https://zgdfsgd.github.io/panda-maze-game/ |
| 📦 GitHub 仓库 | https://github.com/Zgdfsgd/panda-maze-game |
| 🐛 问题反馈 | https://github.com/Zgdfsgd/panda-maze-game/issues |

---

**六一儿童节快乐！🐼🐺✨**

_小时候想当探险家，现在用 TRAE 把追逐游戏做出来了！_

**🌟 觉得有趣的话，欢迎给个 Star⭐ 支持一下！**

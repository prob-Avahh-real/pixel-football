# pixel-football（实况女足 · Pixel Football）

单页 HTML5 Canvas 像素风 2D 足球对局小游戏（中国女足 vs 佛得角男足，已归档于 `archive/from-home/pixel-football`）。

## 玩法与特性

- **实时像素球场**：900×600 Canvas 球场渲染、上下半场计时、开球/暂停/重置及裁判哨声动画提示
- **双模式操控**：支持「半自动 / 手动」切换、传球配合、射门蓄力与实时赛况事件日志（`#eventLog`）
- **零外部运行时依赖**：纯原生 HTML/CSS/JS 单文件即可直接运行

## 目标平台（Target 判定）

- **移动端**：可选（单页 Web 小游戏）
- **智能硬件**：可选（可搁置）

## 快速运行与验证

```bash
# 本地静态服务预览
npx --yes serve .

# 运行归档冒烟测试
npm test
```

# Stylophone GEN X-2 电子琴模拟器

基于 Web Audio API 的网页版 Stylophone 电子琴模拟器，还原经典 Stylophone 的演奏体验。

## 功能特性

- **触控笔演奏** - 逼真的触控笔跟随鼠标移动，悬停琴键即可发声
- **八度切换** - 支持 Low / Mid / High 三档八度切换
- **颤音效果** - 内置 Vibrato 颤音功能，模拟经典 Stylophone 音色
- **延音控制** - Sustain 延音开关，让音符持续发声
- **变调旋钮** - Transpose 旋钮可调节音高偏移
- **左右手模式** - 支持左手 / 右手模式切换，适配不同演奏习惯
- **20 键键盘** - 12 个底部琴键 + 8 个顶部琴键，覆盖完整音域

## 使用方法

直接在浏览器中打开 `index.html` 即可开始演奏，无需安装任何依赖。

## 演示

[演奏效果演示](./play_together.mp4)

欢迎在 [Issue](../../issues) 区分享你的演奏作品，一起交流学习！

## 键盘快捷键

| 快捷键 | 功能 |
|--------|------|
| Z | 切换至 Low 八度 |
| X | 切换至 Mid 八度 |
| C | 切换至 High 八度 |
| V | 开关 Vibrato 颤音 |
| S | 开关 Sustain 延音 |

## 技术实现

项目为单一 HTML 文件，内嵌 CSS 与 JavaScript，使用 Web Audio API 实时合成声音，无需任何外部依赖或构建工具。

## 开发历史

本项目的 Git 提交记录中，不符合常规开源提交规范的消息均为开发时使用的提示词，可通过 `git log` 查看。

## 致谢

本项目使用 [Code With SOLO](https://solo.trae.cn/) 模式开发。

## 许可证

MIT License

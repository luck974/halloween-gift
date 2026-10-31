# 🎃 万圣节快乐 · Happy Halloween

给朋友做的万圣节贺卡网页，单文件 HTML，部署在 GitHub Pages，手机微信可直接打开。

## 打开方式
- 线上链接：https://luck974.github.io/halloween-gift/
- 进入口令：`luck`

## 功能
1. 口令门禁 —— 输入 `luck` 才能进入
2. 打字机祝福 + 飘落雪花 / 蛛网 / 城堡场景
3. 欢快版《欢乐颂》背景音乐（Web Audio 现场合成，无音频文件）
4. 结尾「万圣节幸运签」转盘抽签，带指针音效 + 五彩纸屑

## 想改什么（都在 `index.html` 的 `<script>` 里）
- **口令**：`var GATE_PWD = 'luck'`
- **签文**：`var DRAW_ITEMS = [ ... ]` 数组
- **背景音乐**：`MELODY` / `BASS`（音符频率表在 `NOTE`）

改完 `git push` 即生效（GitHub Pages 约 1 分钟自动更新）。

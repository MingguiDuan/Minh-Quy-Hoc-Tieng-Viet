# Chào Miền Nam

静态站，直接部署到 GitHub Pages（Settings → Pages → Deploy from branch → main / root）。
本地预览：`python3 -m http.server`，打开 http://localhost:8000

## 内容
所有课程内容在 `data/content.json`，改它即可，不用改 HTML。

## 音频命名
`audio/<id>.mp3`，慢速版 `audio/<id>-slow.mp3`。id 就是 JSON 里的 id
（如 `letter-a`、`w-ba`、`t-ma3`、`d1-1`、`r1-1`、`w-v-chao（词汇卡 id 前加 w-）`）。
文件缺失时，页面会临时用浏览器自带朗读代替（口音不保证是南部），仅供调试。
慢速版请让 TTS 直接生成，不要后期变速。

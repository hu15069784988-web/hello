# 星野 · 星空摄影作品集

深色沉浸式静态网站，支持作品分类、全屏欣赏、方向键切换以及手机浏览。

## 浏览网站

已发布版本：https://xingye-cosmic-atlas.hu15069784988.chatgpt.site （目前仅站点所有者可访问）

在本地打开 index.html 即可浏览，无需安装依赖或构建。也可在仓库目录运行 `python -m http.server 8080` 后打开 http://localhost:8080。

## 编辑

- `index.html`：页面内容与结构
- `style.css`：布局、颜色和响应式样式
- `app.js`：作品数据、筛选和全屏交互；修改 `works` 数组可替换照片、标题和署名
- `hero.jpg`、`pillars.jpg`、`galaxy.jpg`：示例天文影像

GitHub 仓库和 Sites 站点不会自动同步，修改后需另行更新已发布的网站。

## 影像来源

示例不是个人原创摄影。请保留每张图片的来源与完整署名；代码的使用许可不覆盖第三方影像。

- 宇宙悬崖：https://esawebb.org/images/weic2205a/ — NASA, ESA, CSA, and STScI
- 创生之柱：https://science.nasa.gov/asset/webb/pillars-of-creation-nircam-image/ — NASA, ESA, CSA, STScI; J. DePasquale, A. Koekemoer, A. Pagan (STScI).
- 幻影星系：https://esawebb.org/images/potm2208a/ — ESA/Webb, NASA & CSA, J. Lee and the PHANGS-JWST Team. Acknowledgement: J. Schmidt

ESA/Webb 影像使用条款：https://esawebb.org/copyright/

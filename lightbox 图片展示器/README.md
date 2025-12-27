# Lightbox2 插件说明
## 需求
Wiki中的**图片展示**需要**点击放大、幻灯片播放**功能，提升用户体验。
## 实现思路
1. 引入Lightbox2的CSS/JS文件；
2. 为图片链接添加`data-lightbox`属性（如`<a href="large.jpg" data-lightbox="set">`）；
3. 无需额外JS，插件会自动绑定事件。
## 优点
- 使用简单：只需添加`data-lightbox`属性，无需编写JS；
- 功能实用：支持放大、幻灯片、缩略图导航；
- 兼容性好：支持所有现代浏览器（Chrome、Firefox、Edge）。

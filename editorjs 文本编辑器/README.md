# Editor.js 插件说明
## 需求
Wiki需要**可视化内容编辑**功能，支持富文本（如标题、段落、图片），替代传统的文本框，提升内容录入效率。
## 实现思路
1. 引入Editor.js的JS/CSS文件；
2. 在HTML中添加一个容器（如`<div id="editorjs"></div>`）；
3. 用JavaScript初始化编辑器（`new EditorJS({ holder: 'editorjs' })`）。
## 优点
- 易用性：无需编写HTML/CSS，只需几行JS即可实现可视化编辑；
- 数据结构化：输出的JSON数据便于存储（可用Python的`json`模块解析）；
- 扩展性：支持添加自定义工具（如表格、代码块）。

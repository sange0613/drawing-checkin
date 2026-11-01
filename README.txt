施工图纸打卡 · Mac 部署说明

1. 解压 ZIP。
2. 打开 https://github.com/sange0613/drawing-checkin
3. 选择 Add file → Upload files，上传 index.html 和 .nojekyll，然后点击 Commit changes。
   Mac 默认隐藏 .nojekyll；按 Command + Shift + . 可显示隐藏文件。
   本网页无需构建，即使只上传 index.html 也可使用。
4. 打开仓库 Settings → Pages。
5. Source 选择 Deploy from a branch，Branch 选择 main，目录选择 /(root)，点击 Save。
6. 等待 GitHub 发布完成，再打开 https://sange0613.github.io/drawing-checkin/

也可直接在 Mac 上双击 index.html 本地打开预览。

功能：点击方块完成或撤销、备注和快捷键、调整顺序、增删图纸、搜索、导出与导入备份、深浅主题切换。
字体：优先使用 Mac 自带的苹方，图纸名称 17px，半粗字重。

重要：进度和笔记保存在当前浏览器中，不会自动跨设备同步。
从原网站换到 GitHub Pages 或 Mac 前，请先在原网页点击“导出备份”，再在新网页“导入备份”。

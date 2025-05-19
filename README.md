# knife4j 文档增强工具（誉存版本）

![Tampermonkey](https://img.shields.io/badge/Tampermonkey-%234D4D4D.svg?style=for-the-badge&logo=Tampermonkey&logoColor=white)

专为 knife4j 文档设计的增强工具，提供一键复制接口代码和模块文件功能，让开发效率起飞~ 🚀

## ✨ 功能亮点

✅ 智能识别当前接口路径  
✅ 自动生成带注释的请求函数  
✅ 支持两种复制模式：

- 📋 单接口复制（精确到当前查看的接口）
- 📁 模块文件复制（整组 API 一键生成）  
  ✅ 可视化操作反馈（成功/错误提示）  
  ✅ 自动加载最新 API 文档数据  
  ✅ 完美样式隔离（不影响原页面布局）

## 📦 快速安装

1. 第一步： 下载安装 Tampermonkey 浏览器插件：
   - [🔗Chrome 插件市场-需梯子](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
   - [🔗 极简插件市场-无须梯子](https://chrome.zzzmh.cn/info/dhdgffkkebhmkfjojejmpbldmpobfkfo)
2. 第二步： 点击安装链接 ➡️ [🔗 一键直达安装脚本](https://update.greasyfork.org/scripts/536050/knife4j%E6%96%87%E6%A1%A3%20API%E6%96%87%E6%A1%A3%E5%A2%9E%E5%BC%BA%E5%B7%A5%E5%85%B7%28%E8%AA%89%E5%AD%98%E7%89%88%29.user.js)

## 📕 使用指南

1. 打开任意 knife4j 文档页面（URL 含`/doc.html`）
2. 在页面右上方看到悬浮工具按钮：

   ```bash
   📋 复制接口/文件
   ```

3. 点击按钮，选择复制模式：
   - 📋 单接口复制：点击后会生成并复制当前接口的请求函数
   - 📁 模块文件复制：点击后会生成并复制当前模块的所有接口函数

## 💡 参考示例
![enter image description here](https://p0-xtjj-private.juejin.cn/tos-cn-i-73owjymdk6/31eebe7c468b4f51945173118f099538~tplv-73owjymdk6-jj-mark-v1:0:0:0:0:5o6Y6YeR5oqA5pyv56S-5Yy6IEAg5bed:q75.awebp?policy=eyJ2bSI6MywidWlkIjoiMjA0OTE0NTQwMzYwOTY4OCJ9&rk3s=e9ecf3d6&x-orig-authkey=f32326d3454f2ac7e96d3d06cdbb035152127018&x-orig-expires=1747724175&x-orig-sign=TJF9DQrvVUXw6zzZ4GWm%2FROlM2w%3D "enter image title here")

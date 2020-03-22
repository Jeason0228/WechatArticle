# Chrome巧取网页素材的方法
## 问题背景
**Case 1:** 之前在做海外League of Runeterra项目的时候，由于官方提供的图标素材实在是太小了，也不是矢量的，因此在设计过程中，可能要求设计师重绘图标，显然这很麻烦。

**Case 2:** 之前在做League of Legends的Banner的时候，发现北美LOL-EPSORT官网的素材非常可以，所以想要把素材都下载下来，研究一番。但是发现有长达60多页的图片数据Json。

做设计的时候，偶尔需要从网页上扒一扒素材，从而避免抠图或者重绘，提高效率。所以今天来聊聊从网上扒素材的方法，Chrome DevTools是Chrome浏览器自带的开发者工具，非常好用。
你可以通过以下办法呼出控制台：
1. 在网页中鼠标右键，点击“审查元素”或“检查”
2. 直接快捷键F12、⌘+⌥ +i（MacOS）、Ctrl+Shift+J 
3. 点击菜单（...） →  更多工具  →  开发者工具
图片：控制台

- ```Elements``` - 查看、编辑和调试HTML、CSS和DOM
- ```Console``` - 调试页面JavaScript脚本最常用的方法，包括调试Log，断点调试，在源代码中调试等
- ```Sources``` - 页面静态资源
- ```Network``` - 对页面请求进行抓包，分析以及做性能优化
- ```Performance``` - 设备加载性能分析
- ```Application``` - 应用信息，PWA/Storage/Cache/Frames,调试客户端存储，包括学会如何对Cookie，LocalStorage等调试
- Security - 安全分析
- Audits - 审计，自动化测试工具
 
那具体有什么用呢
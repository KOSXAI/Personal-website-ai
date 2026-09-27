# Starry Museum — 参考模板 #013

> 在线演示：https://skyjjgw.github.io/starry-museum-portfolio/

## 基本信息

- 名称：Starry Museum / 星夜作品馆
- 源码：[https://github.com/skyjjgw/starry-museum-portfolio](https://github.com/skyjjgw/starry-museum-portfolio)
- 作者原站：[skyjjgw.com](https://skyjjgw.com)（真实个人网站，与匿名模板演示区分）
- X：[@skyjjgw](https://x.com/skyjjgw)
- 联系邮箱：[skyjjgw@gmail.com](mailto:skyjjgw@gmail.com)
- 类型：可 Fork 的匿名模板，所有人物资料和项目均为虚构演示
- 技术栈：静态 HTML / CSS / JavaScript、Three.js，esbuild 生成已附带的运行文件
- 语言：中文展馆导航 + 英文示例展品；没有自动双语切换
- 授权：模板代码 MIT；画作、木纹及动画方向场的来源见源码 ATTRIBUTION.md

## 首页结构

1. 星夜序言：介绍作品集的空间隐喻，滚动进入展览。
2. 问候画框：可点亮的星星和示例简介。
3. 作品画框：选择封面后更新对应的项目介绍。
4. 手记画框：可翻页的过程笔记。
5. 关于画框：带轻微指针倾斜的银色简介卡。
6. 结束邀请：所有画框退出后出现回访作品入口。

## 可吸收的设计要点

- 连贯空间：浮动实木画框与真实 HTML 展品共享投影，而非四张静态截图。
- 梵高背景：整幅《星月夜》沿方向场持续流动，保留暂停和静态回退。
- 直接互动：画框内操作内容；点击框外继续，支持全屏阅读。
- 阅读节奏：可选自动浏览，每幅停留 3 秒、2.4 秒缓慢移动；默认手动。
- 适配能力：小屏使用 1024px 画作、像素比上限 1、30 FPS 上限、渐进加载展品。
- 内容维护：content.js 集中管理虚构资料；导航与开场文案在 index.html 中。

## 适用人群与边界

适合希望用艺术空间串联项目、过程与个人介绍的创作者和开发者。
这是交互模板演示，不是已验证的客户案例；不要把虚构项目作为真实能力背书。
支持减少动态偏好；WebGL 不可用时提供独立展品链接。示例展品仍需要 JavaScript。
不包含后台、数据采集或第二套独立作品集应用。

## 素材

Vincent van Gogh《星月夜》公共领域复制图；Poly Haven CC0 橡木纹理；
DomonJi/InteractiveStarryNight MIT 方向场；Three.js MIT。
完整声明保留在源码，不能将第三方授权替换成模板作者的授权。

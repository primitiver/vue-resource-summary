<h1 align="center">vue开发资源汇总</h1>

本文收集了vue开发过程中会使用到的资料、问题以及第三方组件库。本文不是一篇关于如何学习微信小程序的入门指南，也非参考手册，只是一些资料的整理。

如果这个仓库对你有帮助，欢迎 star。


## 目录

- [官方文档](#官方文档)
- [工具](#工具)
- [PC端UI组件库](#PC端UI组件库)
- [开箱即用中后台管理系统框架](#开箱即用中后台管理系统框架)
- [PC端组件](#PC端组件)
- [移动端UI组件库](#移动端UI组件库)
- [移动端组件](#移动端组件)

## 官方文档

- [vue基础教程](https://v3.cn.vuejs.org/)
- [vue API参考](https://v3.cn.vuejs.org/api/)
- [vue router](https://router.vuejs.org/zh/index.html)
- [vuex](https://vuex.vuejs.org/zh/index.html)
- [vuetools](https://devtools.vuejs.org/)
- [Vue Test Utils](https://test-utils.vuejs.org/guide/)
- [vue CLI](https://cli.vuejs.org/zh/index.html)


[↑ 返回目录 ↑](#目录)

## 工具
- [vscode](https://developers.weixin.qq.com/miniprogram/dev/devtools/devtools.html) - 微软背书强大的开源编辑器
- [vite★36.6k+](https://vitejs.cn/) - 下一代前端开发与构建工具
- [nuxt.js★39.5k+](https://www.nuxtjs.cn/) - SSR服务器端渲染框架
- [postcss-px2rem★500+](https://www.npmjs.com/package/postcss-px2rem) - px转rem移动端必备插件
- [uni-app ★33.8k+](https://github.com/dcloudio/uni-app) - 使用 Vue 语法开发小程序、H5、App的统一框架
- [Taro ★29.8k+](https://github.com/NervJS/taro) - 使用 React 的方式开发小程序的框架，同时支持生成多端应用
- [awesome-fenix ★5.1k+](https://icyfenix.cn/) - 构建可靠的大型分布式系统
- [PicGo ★16.1k+](https://github.com/Molunerfinn/PicGo.git) - 一个用于快速上传图片并获取图片 URL 链接的工具
- [picx ★1.1k+](https://github.com/XPoet/picx.git) - 基于 GitHub API & jsDelivr 开发的具有 CDN 加速功能的图床管理工具。
- [kuboard-press ★13.6k+](https://github.com/eip-work/kuboard-press.git) - 基于 Kubernetes 的微服务管理界面。
- [showdoc ★10.3k+](https://github.com/star7th/showdoc.git) - 一个非常适合IT团队的在线API文档、技术文档工具

[↑ 返回目录 ↑](#目录)

## js类库及工具函数
- [axios ★91.5k+](http://www.axios-js.com/) - Axios 是一个基于 promise 的 HTTP 库，可以用在浏览器和 node.js 中。
- [echarts ★50.1k+](https://echarts.apache.org/zh/index.html) - 一个基于 JavaScript 的开源可视化图表库
- [d3.js ★101k+](https://www.d3js.org.cn/) - 强大的数据图标展示库
- [Moment.js ★46.3k+](https://github.com/moment/moment.git) - javaScript 日期处理类库
- [three.js ★79.7k+](https://github.com/mrdoob/three.js.git) - Three.js 是一款运行在浏览器中的 3D 引擎
- [day.js ★38.1k+](https://dayjs.fenxianglu.cn/) - 一个极简的浏览器解析、验证、操作和显示日期和时间js库
- [turf.js ★1.6k+](https://turfjs.fenxianglu.cn/) - 地理空间分析库，处理各种地图算法js库
- [gantt-elastic ★994k+](https://github.com/neuronetio/gantt-elastic.git) - Gantt-elastic是一个Gantt图表组件，用于项目任务管理的甘特图
- [jsencrypt.js ★5.6k+](https://github.com/jaywcjlove/store.js.git) - 使用RSA加解密
- [normalize.css ★46.8k+](https://github.com/necolas/normalize.css.git) - 一个可以定制的CSS文件，它让不同的浏览器在渲染网页元素的时候形式更统一。
- [qrcodejs ★11.1k+](https://github.com/davidshimjs/qrcodejs.git) - 生成二维码
- [screenfull ★6.4k+](https://github.com/sindresorhus/screenfull.git) - 全屏组件
- [js-cookie ★19.1k+](https://github.com/js-cookie/js-cookie.git) - cookie存取
- [clipboard.js ★31.9k+](https://github.com/zenorocha/clipboard.js.git) - 一款轻量级的实现复制文本到剪贴板功能的JavaScript插件
- [lodash ★52.4k+](https://www.lodashjs.com/) - Lodash 是一个一致性、模块化、高性能的 JavaScript 实用工具库。
- [NProgress.js ★24k+](https://ricostacruz.com/nprogress/) - 浏览器顶部的进度条
- [turndown ★6.1k+](https://github.com/mixmark-io/turndown.git) - 使用 JavaScript 将 HTML 转换为 Markdown
- [js-dom ★17.1k+](https://github.com/jsdom/jsdom.git) - 一款可在 Node 环境下模拟浏览器的 API 的库
- [xray ★6.5k+](https://github.com/chaitin/xray.git) - xray 是一款功能强大的安全评估工具
- [FileSaver.js ★18.6k+](https://github.com/eligrey/FileSaver.js.git) - 可以让你保存较大的文件，不受 blob 的大小限制或内存限制
- [xlsx ★5.2k+](https://github.com/tealeg/xlsx.git) - 可以让你保存较大的文件，不受 blob 的大小限制或内存限制
- [sheet.js ★29.3k+](https://github.com/SheetJS/sheetjs.git) - SheetJS是前端操作Excel以及类似的二维表的最佳选择之一，而js-xlsx是它的社区版本。
- [ZY-Player ★10.7k+](https://github.com/cuiocean/ZY-Player.git) - 跨平台桌面端视频资源播放器.简洁无广告.免费高颜值. 
- [xgplayer ★5k+](https://github.com/bytedance/xgplayer.git) - 西瓜播放器是一个Web视频播放器类库 
- [Administrative-divisions-of-China ★12.3k+](https://github.com/modood/Administrative-divisions-of-China.git) - 中华人民共和国行政区划（五级）：省级、地级、县级、乡级和村级。
- [store.js](https://github.com/travist/jsencrypt.git) - localStorage 存储
- [storage.js ★456](https://github.com/ustbhuangyi/storage.git) - localStorage、sessionStorage 存储
- [pinyin ★6.2](https://github.com/hotoo/pinyin.git) - 转换中文字符为拼音。可以用于汉字注音、排序、检索。



## PC端UI组件库

- [element ★51.7K+](https://element.eleme.cn/#/zh-CN) - Element，一套为开发者、设计师和产品经理准备的基于 Vue 2.0 的桌面端组件库
- [element plus ★14.5K+](https://element-plus.gitee.io/zh-CN/) - 基于 Vue 3，面向设计师和开发者的组件库
- [ant design vue ★14.5K+](https://antdv.com/docs/vue/introduce-cn/) - Ant Design 的 Vue 实现，开发和服务于企业级后台产品



## 开箱即用中后台管理系统框架

- [vue-element-admin ★74.4K+](https://panjiachen.github.io/vue-element-admin-site/zh/) - 基于 vue 和 element-ui实现速搭建企业级中后台系统管理
- [fantastic-admin ★504+](https://hooray.gitee.io/fantastic-admin/) - 一款开箱即用的 Vue 中后台管理系统框架
- [vue-manage-system ★14.5k+](https://github.com/lin-xin/vue-manage-system.git) - 基于 Vue3 + Element Plus 的后台管理系统解决方案
- [naive-ui-admin ★1.9k+](https://github.com/jekip/naive-ui-admin.git) - 基于 Vue3.0、Vite、 Naive UI、TypeScript 的中后台解决方案
- [iview-admin ★16k+](https://github.com/iview/iview-admin.git) - 一款前端管理后台集成解决方案。它基于Vue.js并使用 UI Toolkit iView。
- [vue-admin-better ★11.6k+](https://github.com/chuzhixin/vue-admin-better.git) - 一款支持vue2+element-ui vue3+vire+element plus后台管理系统。
- [CRMEB ★3.5k+](https://github.com/crmeb/CRMEB.git) - CRMEB打通版v4免费开源商城系统，uni-app+thinkphp6框架商城，系统可商用
- [RuoYi-Vue3 ★391](https://github.com/yangzongzhuan/RuoYi-Vue3.git) - 基于SpringBoot+Vue3前后端分离的Java快速开发框架
- [h5-Dooring ★6.4k+](https://github.com/MrXujiang/h5-Dooring.git) - 让H5制作像搭积木一样简单, 轻松搭建H5页面, H5网站, PC端网站,LowCode平台
- [gods-pen ★4K+](https://github.com/ymm-tech/gods-pen.git) - 基于vue的高扩展在线网页制作平台，可自定义组件，可添加脚本，可数据统计。
- [luban-h5 ★5.2K+](https://github.com/ly525/luban-h5.git) - 类似易企秀的H5制作、建站工具、可视化搭建系统.


[↑ 返回目录 ↑](#目录)

## PC端组件
- [vxe-table ★4.5K+](https://vxetable.cn/#/table/start/install) - 基于 vue 的 PC 端强大的表格组件
- [vue-simple-uploader ★1.6K+](https://github.com/simple-uploader/vue-uploader) - 强大的文件上传 Vue 组件
- [vue-draggable ★16.9k+](https://github.com/SortableJS/Vue.Draggable.git) - vue拖拽组件
- [vue-codemirror ★2.2K+](https://github.com/surmon-china/vue-codemirror.git) - 适用于 Vue 的 Web 代码编辑器。
- [vue-i18n ★6.6K+](https://github.com/kazupon/vue-i18n.git) - Vue I18n 是 Vue.js 的国际化插件
- [vue-ueditor-wrap ★1.4K+](https://github.com/haochuan9421/vue-ueditor-wrap.git) - 一个包装了 UEditor 的 Vue 组件
- [tinymce.js ★10.9k+](https://github.com/tinymce/tinymce.git) - 一款易用、且功能强大的所见即所得的富文本编辑器
- [mavonEditor ★5.4k+](https://github.com/hinesboy/mavonEditor.git) - 一款基于 Vue 的 markdown 编辑器，支持所见即所得
- [form-generator ★5.9k+](https://github.com/JakHuang/form-generator) - Element UI表单设计及代码生成器，可将生成的代码直接运行在基于Element的vue项目中
- [Variant Form ★2.2k+](https://www.vform666.com/) - 一款高效的Vue 2低代码表单，可视化设计，一键生成源码
- [vue-form-making ★4.6k+](https://github.com/GavinZhuLei/vue-form-making.git) - 基于Vue的可视化表单设计器，让表单开发简单而高效。
- [x-render ★4.1k+](https://github.com/alibaba/x-render.git) - 阿里 - 很易用的中后台「表单 / 表格 / 图表」解决方案
- [form-create ★3.9k+](https://github.com/xaboy/form-create.git) - 强大的动态表单生成器
- [DataV ★6.6k+](https://github.com/DataV-Team/DataV.git) - DataV是一个基于Vue的数据可视化组件库
- [vxe-table ★4.5k+](https://github.com/x-extends/vxe-table.git) - 一个基于 vue 的 PC 端表格组件，支持增删改查、虚拟列表、虚拟树、懒加载、快捷菜单、数据校验、打印导出、表单渲染、数据分页等
- [vue-area-linkage ★462](https://github.com/dwqs/vue-area-linkage.git) - 省市区联动选择器
- [vue-cropper ★3.3k+](https://github.com/xyxiao001/vue-cropper.git) - 一个优雅的图片裁剪插件
- [vue-photo-preview ★442](https://github.com/826327700/vue-photo-preview.git) - 基于photoswipe的vue图片预览插件
- [vue-ls ★518](https://github.com/RobinCK/vue-ls.git) - 用于操作 Local Storage(本地存储)、Session Storage(会话存储)、Memory(内存存储)。
- [vue-echarts ★6.8](https://github.com/ecomfe/vue-echarts.git) - vue版echart图表

## 移动端UI组件库

- [vant ★19.2K+](https://vant-contrib.gitee.io/vant/#/zh-CN/home) - 有赞前端团队开源的移动端组件库
- [nutui ★4.1K+](https://nutui.jd.com/) - NutUI 是京东风格的移动端组件库
- [uview ★3.4K+](https://www.uviewui.com/) - uView UI 是全面兼容nvue的uni-app生态框架
- [mescroll ★3.9K+](https://github.com/mescroll/mescroll.git) - 精致的下拉刷新和上拉加载 js框架.支持vue,完美运行于移动端和主流PC浏览器

# web-beyes
贝叶官网


#### 对应的数据位置
> 首页————> home.html————>js/model.json
> 核心技术————> core.html————>js/core.json
> 产品服务————> product.html————>js/product.json
> 新闻动态————> news.html————>js/news.json
> 关于贝叶————> beyes.html————>
> 加入我们————> join_us.html————>js/beyes.json

#### 公共组件的引用及使用方法
```
<!-- 头部 -->
<header id="head"></header>
$('#head').load('./components/head.html');

<!-- 脚部 -->
<footer id="foot"></footer>
$('#foot').load('./components/foot.html');
```

#### 公共样式（style/common.css）
除头部脚部样式以外
> .big-title————> 一级标题
> .medium-title————> 二级标题，带绿色左右边框的
> .small-title————> 三级标题，带灰色边框
> .text1————> 文本1，文字居中
> .text2————> 文本2，文字左对齐
> .banners————> 每个页面的banner
> .module————> 带border的模块（首页的核心技术，应用领域，合作伙伴；核心技术模块的核心算法，贝叶科研等）
> .module-item3————> .module里一行有3个div
> .module-item2————> .module里一行有2个div
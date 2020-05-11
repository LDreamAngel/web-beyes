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

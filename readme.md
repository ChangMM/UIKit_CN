---
home: true
footer: GPL3.0 Licensed | Copyright © 2018-present ChangMM
---
<style>
.start-wrap{
  margin:40px auto;
  text-align:center;
}
.start-btn{
  display:inline-block;
  height:50px;
  line-height:50px;
  font-size:20px;
}
</style>

<div style="text-align:center;">
  <img src="./images/logo.png" style="height:100px;"></img>
</div>

<p class="start-wrap">
  <a href="/AboutAppDevelopmentWithUIKit.html" class="start-btn">开始上手→</a>
</p>


### 自己部署

``` bash
# install VuePress
yarn global add vuepress # OR npm install -g vuepress

# git clone repo
git clone git@github.com:ChangMM/UIKit_CN.git && cd UIKit_CN

# start writing
npm run dev

# build to static files
npm run build
```

::: warning COMPATIBILITY NOTE
VuePress requires Node.js >= 8.
:::

# webpack-react
webpack搭建react

### 参考链接
[搭建参考](https://www.jianshu.com/p/04e436cf75ba)

### babel解析
- @babel/core babelbabel的核心库
- @babel/preset-env 把es6,es7语法转换成es5。bebel7以上的版本只用这一个预设包就可以实现语法的转换，已经废弃了preset-stage-0，preset-stage-1，preset-stage-2等这些包。但是这个包还不能转换es6，es7的一些新特性比如Array.includes()，这就需要我们使用@babel/plugin-transform-runtime了
- @babel/preset-react 把react语法转换为es5
- @babel/plugin-transform-runtime 支持一些es6，es7的新语法
- 
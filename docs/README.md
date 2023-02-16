<h1 align="center">
  机器人开发者应懂的33个概念
</h1>

## 简介

这个项目是为了帮助开发者掌握 JavaScript 概念而创立的。它不是必备，但在未来学习（JavaScript）中，可以作为一篇指南。


> 啦啦啦啦，所以本人创立一个中文版，附上关于这些概念在国内的一些文章和视频。啦啦啦啦啦啦啦啦
> 啦啦啦啦

## 更新

若有觉得更好的文章或者视频，可以贡献出来，觉得有误的，请联系我删除。

- 文章的排序优化，前面的文章是介绍概念，后面的文章是深入解读。
- 将原文的 "高阶函数" 和 "map, reduce, filter" 合并为 "map, reduce, filter 等高阶函数"
- 增加 "promise" 概念(替换删除的 "高阶函数")
- 2018-10-24 更新：@BuptStEve 贡献的三篇关于" 函数式编程 "方面的文章
- 2018-12-04 更新：@haner199401 贡献的 @冴羽 "JavaScript 深入之从原型到原型链"

---

## demo

```js
// fake http
function http(res, time = 200) {
  return new Promise((resolve, reject) => {
    setTimeout(_ => {
      var data = mockServer(res)
      console.log('fake server return data: ', data)
      resolve(data)
    }, time)
  })
}
```

## 第三方登录

https://www.ruanyifeng.com/blog/2019/04/github-oauth.html
---
title: Array.prototype.findIndex()
linktitle: Array.prototype.findIndex()
toc: true
type: docs
date: "2019-05-05T00:00:00+01:00"
draft: false
menu:
  oh-my-js:
    parent: Array ES6
    weight: 1

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 1
---

## 描述

`findIndex` 方法用于找出第一个符合条件的数组元素的`索引`。

可参考 [Array.prototype.find](./04-Array.prototype.find.md) 方法，两者作用相同，都是找到符合条件的第一个数组元素，不同之处在于 `find` 方法返回元素值，而 `findIndex` 方法返回元素的**索引**

## 示例

```js
var arr = ['a', 'a', 'b', 'c'];
var item = arr.find(function (item) {
  return item === 'a';
})
var index = arr.findIndex(function (item) {
  return item === 'a';
})
console.log(item);  // "a"
console.log(index);  // 0
```

---
title: Array.prototype.reverse()
linktitle: Array.prototype.reverse()
toc: true
type: docs
date: "2019-05-05T00:00:00+01:00"
draft: false
menu:
  oh-my-js:
    parent: ES3 Array
    weight: 1

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 45
---

## 描述

`reverse()` 方法用于颠倒数组中元素的顺序。（修改原数组）

## 参数

无

## 返回值

返回颠倒顺序后的数组。

## 示例

```js
var numbers = [1, 2, 3, 4];
numbers.reverse();
console.log(numbers); // [4, 3, 2, 1]
```

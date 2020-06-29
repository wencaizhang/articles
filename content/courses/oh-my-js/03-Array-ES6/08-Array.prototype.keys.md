---
title: Array.prototype.keys()
linktitle: Array.prototype.keys()
toc: true
type: docs
date: "2019-05-05T00:00:00+01:00"
draft: false
menu:
  example:
    parent: Array ES6
    weight: 1

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 1
---

## 描述

返回一个包含数组中每个索引的 Array Iterator 对象。

## 示例

```js
var arr = [ 'a', 'b', 'c' ];

var result = arr.keys();

result.next();
// {value: 0, done: false}

result.next();
// {value: 1, done: false}

result.next();
// {value: 2, done: false}

result.next();
// {value: undefined, done: true}

result.next();
// {value: undefined, done: true}
```

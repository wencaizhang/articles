---
title: Array.prototype.entries()
linktitle: Array.prototype.entries()
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

返回一个包含数组中每个索引的键值对的 Array Iterator 对象。

## 示例

```js
var arr = [ 'a', 'b', 'c' ];

var result = arr.entries();

result.next();
// {value: [0, "a"], done: false}

result.next();
// {value: [1, "b"], done: false}

result.next();
// {value: [2, "c"], done: false}

result.next();
// {value: undefined, done: true}

result.next();
// {value: undefined, done: true}
```
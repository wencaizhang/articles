# Hugo Academic Site

基于 Hugo 和 Academic 的静态网站

环境要求：hugo

使用步骤

1. 克隆代码：

```bash
git clone https://github.com/wencaizhang/blog.git My_Website
```

2. 拉取主题代码

```bash
cd My_Website
git submodule update --init --recursive
```

3. 启动服务

```bash
hugo server -D
```

4. 编译为静态文件

```bash
hugo --minify
```
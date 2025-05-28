# CSS 资源目录

## 说明

此目录原本包含网站使用的CSS资源文件，主要是Font Awesome图标库。

## 当前状态

为了提高网站性能和可维护性，我们已将Font Awesome的引用改为使用CDN：

```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
```

## 原始文件结构

```
├── font-awesome
│   ├── all.min.css
│   └── webfonts
│       ├── fa-brands-400.woff2
│       ├── fa-regular-400.woff2
│       ├── fa-solid-900.ttf
│       └── fa-solid-900.woff2
└── webfonts
    ├── fa-brands-400.woff2
    ├── fa-regular-400.woff2
    ├── fa-solid-900.ttf
    └── fa-solid-900.woff2
```

## 备注

- 如果需要离线使用，可以下载Font Awesome并放置在此目录中
- 确保更新HTML文件中的引用路径
- 当前版本使用的是Font Awesome 6.4.0

## 使用CDN的优势

1. 减少仓库大小
2. 提高页面加载速度
3. 利用浏览器缓存
4. 自动获取最新的安全更新
5. 减少服务器带宽使用
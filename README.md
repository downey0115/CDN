# CDN
hexo 图床

感谢 [Jsdelivr](https://www.jsdelivr.com/) 为本仓库提供免费 CDN 服务

根链接：https://cdn.jsdelivr.net/gh/downey0115/CDN

通过jsDelivr引用资源

```
https://cdn.jsdelivr.net/gh/downey0115/CDN/
```

```
使用方法：https://cdn.jsdelivr.net/gh/你的用户名/你的仓库名@发布的版本号/文件路径
例如：

- https://cdn.jsdelivr.net/gh/downey0115/CDN/configuration/avatar.jpg
注意：版本号不是必需的，是为了区分新旧资源，如果不使用版本号，将会直接引用最新资源，除此之外还可以使用某个范围内的版本，查看所有资源等，具体使用方法如下：

- // 加载任何Github发布、提交或分支
  https://cdn.jsdelivr.net/gh/user/repo@version/file
- // 加载 jQuery v3.2.1
  https://cdn.jsdelivr.net/gh/jquery/jquery@3.2.1/dist/jquery.min.js
- // 使用版本范围而不是特定版本
  https://cdn.jsdelivr.net/gh/jquery/jquery@3.2/dist/jquery.min.js
  https://cdn.jsdelivr.net/gh/jquery/jquery@3/dist/jquery.min.js
- // 完全省略该版本以获取最新版本
  https://cdn.jsdelivr.net/gh/jquery/jquery/dist/jquery.min.js
- // 将“.min”添加到任何JS/CSS文件中以获取缩小版本，如果不存在，将为会自动生成
  https://cdn.jsdelivr.net/gh/jquery/jquery@3.2.1/src/core.min.js
- // 在末尾添加 / 以获取资源目录列表
  https://cdn.jsdelivr.net/gh/jquery/jquery/
```

### 目录

规范的对文件进行分类，避免修改路径，保证链接的永久性。

```directory
- blog 博客使用的文件
  - configuration 配置文件
  - posts 博文插图
  - top 头图或背景图
```


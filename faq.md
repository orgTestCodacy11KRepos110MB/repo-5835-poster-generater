# 常见问题列表

## 这是一个项目？
用于后端渲染图片的一个项目。

## 主要解决什么问题？
* 各客户端渲染图片不一致
* 提高开发效率（偷懒），如开发、调试、修改

## 怎么安装/使用?
[点这里](https://blog.janguly.com/poster)

## 怎么保证性能？
* 支持结果缓存，相同的 `海报配置` 不会重复渲染，一次渲染持续保存，速度更快。
* 支持模板图片，减少网络图片加载，运行目录下新建 `templates` 文件夹，支持多种图片格式。
* 缓存网络图片，减少网络图片加载。

## 中文乱码怎么解决？
服务器安装中文字体

## 有没有前端页面用于编辑？
目前没有，请求助于开源社区的朋友们

## 有没有演示接口？
http://121.36.71.186:8000/poster/render
> 请勿用于生产环境


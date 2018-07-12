# NewbeeGuide-barkend

后端的方向过于广泛, 这里仅仅是给出各个方向都应该掌握的基础部分

根据我个人的经验得出的学习路线推荐, 除了**前提**外, 其他部分都是建议性的

## 前提

**前提**的意思是: 如果这部分无法做到, 那么放弃是你最好的选择

- [提问的智慧](https://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way/blob/master/README-zh_CN.md)

## 基础

**基础**部分是我极力推荐需要掌握的部分, 后续的学习与这部分有着依赖关系

- Linux 基础
- git 基础

虽然这些技能属于基础, 但也并不需要将过多的精力放在这部分. 我的建议是, 先能够使用 Linux 和 git 生存下来, 之后遇到问题的时候再去提问也是可以的.

Linux 推荐的书是 <鸟哥的 Linux 私房菜>, 在刚开始学的时候, 只要粗略的过一遍即可(甚至于可以只看目录).

git 推荐的书是 <GitHub 入门与实践>, 同样的, 只要先看前三章即可.

## 进阶

- Python
- MySQL
- Docker

## 实践

### Markdown 在线渲染器

- [GitHub 的 Markdown 渲染 API](https://developer.github.com/v3/markdown/)
- [GitHub 的 Markdown 样式](https://github.com/primer/primer/tree/master/modules/primer-markdown)
- [GitHub 的 代码高亮样式](https://github.com/primer/github-syntax-light)

创建自己的在线 Markdown 渲染器, 要求生成和 GitHub 相同的样式, 并且可以下载源代码和样式文件.

生成的过程不能有页面跳转, 你应该使用 Ajax 来获得数据并渲染.

### 提交量图表

编写爬虫, 统计各大 OJ 的提交量, 使用 cron 定时任务, 定时自动执行爬虫

将爬取的数据存入数据库, 编写 WEB 页面用于显示这些信息, 同时可以对比各个 OJ 的提交量

### 静态文件服务器

- [Tinyhttpd](https://github.com/EZLippi/Tinyhttpd)

阅读 Tinyhttpd 代码, 实现自己的静态文件服务器

需要监听某个端口, 根据用户访问的 url 去寻找指定的文件并返回

根据文件的类型不同, 修改返回头的 ```Content-Type```, 以保证浏览器可以正常下载该文件

## 然后我该干什么

这之后应该干什么我也没有办法告诉你了, 到这里之后, 再要做什么就全要看你自己的了, 加油吧

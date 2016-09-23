# Lab2 主题: 版本控制 & 文档

### 版本控制：
1. 为什么要做版本控制？

2. 怎么做版本控制？
<br/>　本次课程选择使用 *Git* 进行版本控制，并将仓库托管在 Github 上。对于 Git 的工作原理，有兴趣的可自己了解([Git 内部原理](https://git-scm.com/book/zh/v2/Git-%E5%86%85%E9%83%A8%E5%8E%9F%E7%90%86-%E5%BA%95%E5%B1%82%E5%91%BD%E4%BB%A4%E5%92%8C%E9%AB%98%E5%B1%82%E5%91%BD%E4%BB%A4))。下文将大致介绍 Git 的工作流程。

##### 关于 Github
　Github 是一个基于 Git 的在线仓库，提供了网页供用户管理仓库
##### 关于 Git
1. 安装 Git 
   [Git 安装参考](https://git-scm.com/book/zh/v2/%E8%B5%B7%E6%AD%A5-%E5%AE%89%E8%A3%85-Git)，图形化&命令行工具都可以。

2. 基本的 Git 工作流包括：
> References:
> 　[git几步走](http://durant35.github.io/2016/07/26/tool_git%E5%87%A0%E6%AD%A5%E8%B5%B0/#more)

```sh
# 拷贝在github上的仓库xxxx(如: https://github.com/CPSinSYSU/ES2016_16214269.git)为你仓库的地址
git clone xxxx
	
# 将 README.md 文件添加到仓库中
git add README.md
	
# 向提交本次修改
git commit -m "xxx"
	
# 向远程仓库（比如 Github）提交本次修改
git push
```

### 文档：
1. 本次文档应该基于**markdown**，并包含下述内容
   * Description
   <br/>　**DOL** 框架描述(随着实验进行迭代添加、修改)
   * How to install
   <br/>　**DOL** 安装笔记
   * Experimental experience
   <br/>　实验感想、实验心得
2. 建议图文并茂、言简意赅

##### 关于markdown
　很容易排版，结合markdown语法和所见即所得的编辑器很容易调整。

1. markdown 语法
   请参考[此处](http://www.jianshu.com/p/1e402922ee32/)

2. WYSIWYG. markdown编辑器
   * markdownpad2
   * typora
   * maxiang
   * mweb
   * cmd markdown
   * 若干在线markdown编辑器
   * 等等

## 本次作业要求：
1. 在 [github](www.github.com)上创建一个仓库，仓库必须命名为 *"ES2016_学号"*，**该仓库将作为本门课程的实验课的评分依据，我们承诺期末前会看完每个仓库**
2. 基于配置 DOL 的过程，写一个文档，命名为 **README.md**
3. 将该文件添加到 **github** 上你的仓库中
4. 在 [此处](http://www.chaojibiaoge.com/index.php/U/url/czKJgPol) 填写你对应的信息，包括学号、姓名、你所创建的仓库的 url 地址如："*https://github.com/CPSinSYSU/ES2016_16214269*", **该信息登记将于 10:10, 10th October, 2016 关闭**



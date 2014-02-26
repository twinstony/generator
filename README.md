# generator

## 安装

以下带 `-g` 的命令是在root 用户下执行的，如果出现权限问题 请使用sudo命令，例如`sudo npm install -g yo`

### HomeBrew 的安装

在 OS X 中找不到您想要的软件？[Homebrew](http://brew.sh/index_zh-cn.html) 给你所需。


### NodeJS安装

```
brew install node
```

### Grunt

```
npm install -g grunt-cli
```

### Compass
因为Sass和Compass依赖Ruby环境，所以你首先需要[安装Ruby](http://www.ruby-lang.org/en/downloads/)，安装好以后执行

注意：必须安装1.9.x以上的Ruby版本

```
gem install compass
```

上面的开发利器都装好了，我们开始安装我们的Generator


## 运行

安装好以后执行

```
grunt
```

浏览器将自动打开预览地址，这时候查看你的项目根目录，有一个.tmp的目录，这个目录为临时build出来供你预览的目录。



## 技术介绍
采用Grunt作为构建工具，CSS使用Sass+Compass编写，HTML采用Jade编写。所在在参与前，需要了解基本的Sass,Jade。

[Sass用法指南](http://www.ruanyifeng.com/blog/2012/06/sass.html)

[Compass用法指南](http://www.ruanyifeng.com/blog/2012/11/compass.html)

[Jade模板引擎入门教程](https://github.com/visionmedia/jade/blob/master/Readme_zh-cn.md)

[CoffeeScript使用说明](http://coffeescript.org/)

这几个都很简单，花两个小时了解下，使用两天后，你会发现你的开发效率有飞速的进步。

# Hugo

Hugo是一个用Go语言编写的静态网站生成器，它使用起来非常简单，相对于Jekyll复杂的安装设置来说，Hugo仅需要一个二进制文件hugo(hugo.exe)即可轻松用于本地调试和生成静态页面。

Hugo生成静态页面的效率很高，我的260多篇博客文章生成几乎是瞬间完成的，而之前用Jekyll需要等待10秒左右。

Hugo自带watch的调试模式，可以在我修改MarkDown文章之后切换到浏览器，页面会检测到更新并且自动刷新，呈现出最终效果，能极大的提高博客书写效率。再加上Hugo是使用Go语言编写，已经没有任何理由不使用Hugo来代替Jekyll作为我的个人博客站点生成器了。


# Usage

```
git submodule init
git submodule update
```

### 启动调试

```
$ python debug.py
```

或者

```
$ hugo server -w -t hugo-tranquilpeak-theme
```

打开浏览器：http://localhost:1313

### 部署

参考 `deploy.py`

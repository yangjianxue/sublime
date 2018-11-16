# sublime

##### 安装 package control组件
```
功能：可以在线安装需要点组件
安装步骤：
1、ctrl+` 调出console
2、import urllib.request,os; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); open(os.path.join(ipp, pf), 'wb').write(urllib.request.urlopen( 'http://sublime.wbond.net/' + pf.replace(' ','%20')).read())
3、安装完成后重启sublime 
4、如果perferences 里有 package control 则安装成功
```
##### 安装 插件
```
按下Ctrl+Shift+P调出命令面板
输入install 调出 Install Package 选项并回车，然后在列表中搜索要安装的插件。
```

##### sublime 常用插件
```
1、Emmet（原名 Zen Coding）
  功能：一种快速编写html/css的方法
2、html5
  功能：新建文档--输入html5--tab--自动补全html5规范文档
3、Alignment
  功能：代码对齐，如写几个变量，选中这几行，Ctrl+Alt+A，哇，齐了。
4、All Autocomplete
  功能：搜索所有打开的文件来寻找匹配的提示词
5、CTags
  功能：方法跳转，跳转到你方法
  使用：之后在win7下或者linux下安装ctags软件
       打开ctags插件包的use-setting配置"command": "d:/IDE/ctags58/ctags.exe"这个路径是下载ctags的安装路径
这个插件能跨文件跳转，跳转到指定函数声明的地方(ctrl+alt+左键)。 使用package control 搜索ctags 进行安装（安装ctags插件就可以了， 还有一个 CTags for PHP 插件没什么用）,注意安装好插件后要需要安装ctags命令。window 下载 ctags.exe  http://vdisk.weibo.com/s/7QZd7 。 将ctags.exe文件放在一个环境变量能访问到的地方。打开cmd， 输入ctags，如果有这个命令，证明成功了。ubuntu下安装运行命令：sudo apt-get install exuberant-ctags 。然后在sublime项目文件夹右键， 会出       现Ctag:Rebuild Tags 的菜单。点击它，然后会生成.tags的文件 然后在你代码中， 光标放在某个函数上， 点击 就可以跳转到函数声明的地方。
6、AutoFileName
  功能：快速帮助你在文件中写路径整体来说还不错
7、Autoprefixer
  功能：这个插件主要应用css的浏览器兼容书写，自动分析你的css文件，解析出新的css文件，可以配置你要兼容的浏览器，不过这个插件要在之前安装nodejs
8、Color Highlighter
  功能：颜色功能还是很爽的
9、DocBlockr
  功能：自动补全注释插件 （支持JavaScript (including ES6), PHP, ActionScript, Haxe, CoffeeScript, TypeScript, Java, Apex, Groovy, Objective C, C, C++ and Rust.等众多语言）  
10、SublimeTmpl
快速格式化代码
11、Can I Use
可以直接调整到caniuse看到当前属性的浏览器支持情况。快捷键
12、InsertDate
插入时间，项目文件存在CDN的时候，需要改变时间戳才会看到效果，这个是个好东西。
13、Git
Git插件，提供Git常用的命令集合。
```
##### 关于 vue 插件
```
1、Vue Syntax  Highlight 
功能： vue 语法高亮
```

##### 关于 css 插件
```
1、Less
功能： Sublime Text3支持Less
2、Sass
功能： Sublime Text3支持Sass
```

##### 关于 typescript 插件
```
1、TypeScript
功能： TypeScript 语法高亮

```

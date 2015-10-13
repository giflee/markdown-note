##markdown用法笔记
####1、自动连接
<http://ele.me>
####2、代码
`winsow.onload = function(){}`

Please don't use any `<blink>` tags.
####3、强调
**强调**

__强调__

*em*
_em_
####3、链接
[饿了么](http://ele.me)

This is [an example][id] reference-style link.
####4、分割线
***
* * *
___
______________
_ _ _
####5、代码块
	window.onload = function(){
		var abc = 1;
	}
	<div class="footer">
        &copy; 2004 Foo Corporation
    </div>
####6、无序列表
*  游泳
*  跑步
*  运动
+ 跑步
- 运动

####7、区块
> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
> 
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> 
> id sem consectetuer libero luctus adipiscing.
> 
> > > > > > > > >This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
id sem consectetuer libero luctus adipiscing.
4<5
####7、图片
![图片](/Users/jianfulee/Documents/创新中心竞赛部项目/img/link-con-back.png)


``` bash
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```


```
brew install node

```

##09.gulp基本用法
##### 全局安装gulp

```bash
$ npm install --global gulp
```
##### 作为项目的开发依赖（devDependencies）安装：
```bash
$ npm install --save-dev gulp
```
##### 在项目根目录下创建一个名为 gulpfile.js 的文件：
```bash
$ var gulp = require('gulp');

gulp.task('default', function() {
  // 将你的默认的任务代码放在这
});
```
##### 运行 gulp：
```bash
$ gulp
```
    
    

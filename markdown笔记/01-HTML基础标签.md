**学习时间：2022.11.05**
[toc]
# HTML基础标签
## 排版标签
### 标题标签
```html
	<h1>1号标签</h1>
    <h2>2号标签</h2>
    <h3>3号标签</h3>
    <h4>4号标签</h4>
    <h5>5号标签</h5>
    <h6>6号标签</h6>
```
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>1号标签</h1>
    <h2>2号标签</h2>
    <h3>3号标签</h3>
    <h4>4号标签</h4>
    <h5>5号标签</h5>
    <h6>6号标签</h6>
</body>
</html>
```
在浏览器中查看结果如下
![在这里插入图片描述](https://img-blog.csdnimg.cn/eaaa2e75eb2a41618e712750013e4634.png)
### 段落标签
```html
<p> <\p>
```
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p>这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话</p>
    <p>这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一</p>
</body>
</html>
```
浏览器查看如下
![在这里插入图片描述](https://img-blog.csdnimg.cn/3cf6b82cd2c3492688b81bef9ad193ec.png)
### 换行标签
```html
<br> <!-- 强制换行 -->
```
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p>这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话</p>
    <p>这里有一段话这里有一段话这里有一段话。<br>这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一</p>
</body>
</html>
```
浏览器查看如下
![在这里插入图片描述](https://img-blog.csdnimg.cn/1589e2266f0f437b8148816f6af6a225.png)
### 水平线标签
```html
<hr><!-- 分割不同主题内容的水平线 -->
```
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>headline</h1>
    <hr>
    <p>这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话</p>
    <p>这里有一段话这里有一段话这里有一段话。<br>这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一段话这里有一</p>
</body>
</html>

```
浏览器查看如下
![在这里插入图片描述](https://img-blog.csdnimg.cn/70b453decc804560a847dfbf3ea56dc6.png)

## 文本格式化标签
![文本格式化标签的介绍](https://img-blog.csdnimg.cn/3603b18955d3437f919f7bac2f0a7099.png)
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <b>b加粗</b>
    <strong>strong加粗</strong>
    <br>
    <u>u下划线</u>
    <ins>ins下划线</ins>
    <br>
    <i>i倾斜</i>
    <em>em倾斜</em>
    <br>
    <s>s删除</s>
    <del>del删除</del>
</body>
</html>
```

浏览器查看如下

![在这里插入图片描述](https://img-blog.csdnimg.cn/05a5292fca964b5094987ecdf8b032e5.png)
```
strong, ins, em,del的语义较b. u, i, s更为强烈。
也就是，如果这个内容你觉得重要，就放到前4个里面(strong等)。
```
## 媒体标签
### 图片标签



```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <img src="./images/cat.gif" alt="这里是一张猫图" title="可爱猫猫" height="500" width="800">
</body>
</html>
```


#### src属性
图片路径。
正常显示如下
![在这里插入图片描述](https://img-blog.csdnimg.cn/93e5d606bc79495f9fa6e0593dc400a6.png)
#### alt属性
替换文本。
当前图片无法显示时会出现的文字
![在这里插入图片描述](https://img-blog.csdnimg.cn/76c7893aa6504964bebfc982371a8bb0.png)
#### title属性
提示文本。
当鼠标悬停的时候会出现的文本。
![在这里插入图片描述](https://img-blog.csdnimg.cn/98ee6b6b19184c9c8b857c434383d57a.png)
#### height和width属性
图片的高度和宽度(数字表示)
![在这里插入图片描述](https://img-blog.csdnimg.cn/a150ccaf87d04004b483b128706ba7d0.png)
#### 路径
##### 绝对路径
目录下的绝对位置
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <img src="C:\Users\15025\Desktop\前端\HTML\day01\images\cat.gif" alt="">
</body>
</html>
```
##### 相对路径
###### 图片与html文件处于同级或下级
从当前文件出发的路径
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <!-- 图片与该HTML文件处于同级 -->
    <img src="./cat.gif" alt="">
    <img src="dog.gif" alt="">
    <!-- 图片位于该HTML文件下级 -->
    <img src="./images/cat.gif" alt="">
    <img src="images/dog.gif" alt="">
    <!-- 图片位于该HTML文件上级 -->
    <img src="../cat.gif" alt="">
</body>
</html>
```
### 音频标签
![在这里插入图片描述](https://img-blog.csdnimg.cn/c4d8cf952c2446f5a9d44992f2748260.png)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <audio src="./images/music.mp3" controls autoplay loop></audio>
</body>
</html>
```
浏览器显示如下

![在这里插入图片描述](https://img-blog.csdnimg.cn/c186c220725741bfa91e74da49b8b230.png)

### 视频标签
![在这里插入图片描述](https://img-blog.csdnimg.cn/b223cf70267340d1ad7dbdf4f6728f77.png)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <!-- 谷歌浏览器可以自动播放，但必须是静音播放，使用muted标签 -->
    <video src="./images/video.mp4" controls autoplay loop muted></video>
</body>
</html>

```
浏览器显示如下
![在这里插入图片描述](https://img-blog.csdnimg.cn/33e23a21d280401a87e394dff3c4e434.png)
## 链接标签
![在这里插入图片描述](https://img-blog.csdnimg.cn/9d52fe23ad3642d790df89ac494a3237.png)
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <a href="https://cn.bing.com/">跳转至必应</a>
    <br>
    <a href="./01-标题标签.html">跳转至01-标题标签</a>
    <br>
    <!-- 网站开发初期，不知道具体要跳转的地址时，用#即可，称为空链接 -->
    <a href="#">这是一个空链接</a>
    <br>
    <a href="https://cn.bing.com/" target="_blank">跳转至必应并且保留原网页</a>
</body>
</html>
```
浏览器显示如下
![在这里插入图片描述](https://img-blog.csdnimg.cn/6c6d976343494ae8a40d0f1294982812.png)

### target属性
![在这里插入图片描述](https://img-blog.csdnimg.cn/72cba727ed1f4a238418e99eabf1773e.png)


## 快捷键和VScode基本操作
### Ctrl+d
选中要修改的某个字符，按下快捷键后会再选中之后相同的字符
![](https://img-blog.csdnimg.cn/9d65bf6205ea411f929b37a8f8e8f366.png)
图片不太清楚但是可以看到3个3都被选中了
### 自动换行
有些段落文字很长，全放在一行很不方便，在最上方点查看(view)，里面有自动换行选项(Word Wrap)，点击即可

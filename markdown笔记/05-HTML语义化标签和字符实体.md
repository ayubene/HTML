**学习时间：2022.11.05**
[toc]
# HTML语义化标签和字符实体
## 语义化标签
### 没有语义的布局标签
#### div
一行只显示一个（独占一行）
#### span
一行可显示多个
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
    <div>这是div标签</div>
    <div>这是div标签</div>

    <span>这是span标签</span>
    <span>这是span标签</span>
</body>
</html>
```
![在这里插入图片描述](https://img-blog.csdnimg.cn/ef3f37b7dd0b4cb995cee9d50827f767.png)
### 有语义的布局标签
用于手机端网页
![在这里插入图片描述](https://img-blog.csdnimg.cn/054356f1d5054d4fa71ff6b547ef45de.png)
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
    <header>网页头部</header>
    <nav>网页导航</nav>
    <footer>网页底部</footer>
    <aside>网页侧边栏</aside>
    <section>网页区块</section>
    <article>网页文章</article>
</body>
</html>
```
![在这里插入图片描述](https://img-blog.csdnimg.cn/ede3c731be914843a0b05e9e54ca764d.png)

## 字符实体
![在这里插入图片描述](https://img-blog.csdnimg.cn/31e790c37f81424f897742467a135bfb.png)
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
    <!-- 只能识别出一个空格 -->
    这是一段话有         很长的空格<br>
    这是一段话有&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;很长的空格
</body>
</html>
```
![在这里插入图片描述](https://img-blog.csdnimg.cn/75c45ec24476426f811dac2338633382.png)

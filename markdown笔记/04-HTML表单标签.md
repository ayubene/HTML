**学习时间：2022.11.05**
[toc]
# HTML表单标签
## input系列标签
### type属性值
![在这里插入图片描述](https://img-blog.csdnimg.cn/db6d3a88e4d04b299444e17e2ddab54c.png)
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>input标签</title>
</head>
<body>
    文本框<input type="text">
    <br>
    密码<input type="password">
    <br>
    单选框<input type="radio">
    <br>
    多选框<input type="checkbox">
    <br>
    文件选择<input type="file">
    <br>
    提交按钮<input type="submit">
    <br>
    重置按钮<input type="reset">
    <br>
    普通按钮<input type="button">
</body>
</html>
```
![在这里插入图片描述](https://img-blog.csdnimg.cn/5e7aa7aa2f9b4b869459224416834212.png)
### 占位符
![在这里插入图片描述](https://img-blog.csdnimg.cn/bc29f0965f4546d9afb86ce1b8ef170f.png)
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>input标签</title>
</head>
<body>
    文本框<input type="text" placeholder="请输入用户名">
    <br>
    密码<input type="password" placeholder="请输入密码">
    
</body>
</html>
```
![在这里插入图片描述](https://img-blog.csdnimg.cn/e4059bfc2f2c4f4aa8f2a03693c7ac48.png)
### 单选功能和默认选中
![在这里插入图片描述](https://img-blog.csdnimg.cn/dd5ca1c2385b46efb9ecb04f0b48f957.png)
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>单选功能</title>
</head>
<body>
    性别 女<input type="radio" name="gender" checked>
         男<input type="radio" name="gender">
</body>
</html>
```
![在这里插入图片描述](https://img-blog.csdnimg.cn/a2b86ec3a7d447f79d2ef1f26fe912b1.png)
### 文件选择
![在这里插入图片描述](https://img-blog.csdnimg.cn/03b64b2141cf4ad99421fad43056adfe.png)

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
    <input type="file" multiple>
</body>
</html>
```
![在这里插入图片描述](https://img-blog.csdnimg.cn/ac3e059a62b54d4183fa70f1fb1a3191.png)
### 表单域标签
```
<form action=""></form>
```
将整个表单内容放入表单域标签，提交和重置按钮才可以用。
### 按钮
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>按钮</title>
</head>
<body>
    <form action="">
        用户名 <input type="text">
        <br>
        <br>
        密码 <input type="password">
        <br>
        <br>
        <input type="submit">
        <input type="reset">
        <input type="button" value="由js添加功能">
    </form>
</body>
</html>
```
![在这里插入图片描述](https://img-blog.csdnimg.cn/44e624713f4d49308ac59341607bbb5b.png)
## button按钮标签
![](https://img-blog.csdnimg.cn/348c842d0b6e4ebcaf2a0d952ed893ec.png)
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
    <button type="submit">button标签提交按钮</button><br>
    <button type="reset">button标签重置按钮</button><br>
    <button type="button">button标签普通按钮</button><br>
</body>
</html>
```
![在这里插入图片描述](https://img-blog.csdnimg.cn/a0a305d064014c6ba0d921c75abc4ac6.png)
## select下拉菜单标签
![在这里插入图片描述](https://img-blog.csdnimg.cn/0cdac8a5c43f43a8a8ae3a21d4678826.png)
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>下拉菜单</title>
</head>
<body>
    <select>
        <option>北京</option>
        <option>上海</option>
        <option selected>广州</option>
        <option>深圳</option>
    </select>
</body>
</html>
```
## textarea文本域标签
![在这里插入图片描述](https://img-blog.csdnimg.cn/b410aaeca20940b694c50fe2d5f0fe7c.png)
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
    <textarea cols="30" rows="10"></textarea>
</body>
</html>
```
![在这里插入图片描述](https://img-blog.csdnimg.cn/f085521d8fd241a19d7eb8336e16e639.png)
右下角的拖拽功能可以通过css去禁用
## label标签
![在这里插入图片描述](https://img-blog.csdnimg.cn/5c5eb4ca2aa0471a8bb50b1f8bf36a0f.png)
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>label</title>
</head>
<body>
    <!-- 方法1 -->
    性别 <label for="girl">女</label> <input type="radio" name="gender" id="girl">
         <label for="boy">男</label> <input type="radio" name="gender" id="boy">
    <!-- 方法2 -->
    性别 <label>女 <input type="radio" name="gender"></label>
         <label>男 <input type="radio" name="gender"></label>
</body>
</html>
```
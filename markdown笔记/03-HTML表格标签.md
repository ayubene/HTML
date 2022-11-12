**学习时间：2022.11.05**
[toc]
# HTML表格标签
## 基本标签
![在这里插入图片描述](https://img-blog.csdnimg.cn/3d8f4ca3da66433dbb6f08918ff584c9.png)
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>表格的基本使用</title>
</head>
<body>
    <table>
        <tr>
            <td>姓名</td>
            <td>性别</td>
            <td>成绩</td>
        </tr>
        <tr>
            <td>韩梅梅</td>
            <td>女</td>
            <td>100</td>
        </tr>
        <tr>
            <td>李明</td>
            <td>男</td>
            <td>98</td>
        </tr>
    </table>
</body>
</html>
```
![在这里插入图片描述](https://img-blog.csdnimg.cn/42b04382bc72416b985e42ce7e28a1e8.png)

## 基本属性
![在这里插入图片描述](https://img-blog.csdnimg.cn/b46a72e510ca4e3c978dc91baeac63ef.png)
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>表格的基本使用</title>
</head>
<body>
    <table border="4" width="400" height="200">
        <tr>
            <td>姓名</td>
            <td>性别</td>
            <td>成绩</td>
        </tr>
        <tr>
            <td>韩梅梅</td>
            <td>女</td>
            <td>100</td>
        </tr>
        <tr>
            <td>李明</td>
            <td>男</td>
            <td>98</td>
        </tr>
    </table>
</body>
</html>
```
![在这里插入图片描述](https://img-blog.csdnimg.cn/014684c1788a4900823ba48df910530c.png)
## 表格标题和表头单元格标签
![在这里插入图片描述](https://img-blog.csdnimg.cn/e3c67421a448492894062a675d055984.png)
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
    <table border="2" width="300" height="80">
        <caption>学生成绩单</caption>
        <tr>
            <th>姓名</th>
            <th>性别</th>
            <th>成绩</th>
        </tr>
        <tr>
            <td>韩梅梅</td>
            <td>女</td>
            <td>100</td>
        </tr>
        <tr>
            <td>李明</td>
            <td>男</td>
            <td>98</td>
        </tr>
    </table>
</body>
</html>
```
![在这里插入图片描述](https://img-blog.csdnimg.cn/ccd1e09110a74b08a24999044a128b14.png)
## 表格的结构标签
![在这里插入图片描述](https://img-blog.csdnimg.cn/bead60ff531f4f35bff656e83475430b.png)

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
    <table border="2" width="300" height="80">
        <caption>学生成绩单</caption>
        <thead>
            <tr>
                <th>姓名</th>
                <th>性别</th>
                <th>成绩</th>
            </tr>
        </thead>
        
        <tbody>
            <tr>
                <td>韩梅梅</td>
                <td>女</td>
                <td>100</td>
            </tr>
            <tr>
                <td>李明</td>
                <td>男</td>
                <td>98</td>
            </tr>
        </tbody>
        
        <tfoot>
            <tr>
                <td>总结</td>
                <td></td>
                <td></td>
            </tr>
        </tfoot>
        

    </table>
</body>
</html>
```

## 合并单元格
![在这里插入图片描述](https://img-blog.csdnimg.cn/268fc95257814af3a9c29a7c3c0c859f.png)
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
    <table border="2" width="300" height="80">
        <caption>学生成绩单</caption>
        <thead>
            <tr>
                <th>姓名</th>
                <th>性别</th>
                <th>成绩</th>
            </tr>
        </thead>
        
        <tbody>
            <tr>
                <td>韩梅梅</td>
                <td>女</td>
                <!-- 跨行合并 -->
                <td rowspan="2">100</td>
            </tr>
            <tr>
                <td>李明</td>
                <td>男</td>
            </tr>
        </tbody>
        
        <tfoot>
            <tr>
                <td>总结</td>
                <!-- 跨列合并 -->
                <td colspan="2"></td>
            </tr>
        </tfoot>
        

    </table>
</body>
</html>
```
![在这里插入图片描述](https://img-blog.csdnimg.cn/310fa4da6189432faabe38d03f505e65.png)

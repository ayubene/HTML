**学习时间：2022.11.05**
[toc]
## HTML列表标签
### 无序列表
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>无序列表</title>
</head>
<body>
    <h1>水果列表</h1>

    <ul>
        <li>苹果</li>
        <li>橘子</li>
        <li>香蕉</li>
        <li>梨</li>
    </ul>
</body>
</html>
```
![在这里插入图片描述](https://img-blog.csdnimg.cn/ac0c738ca8bc49a2871a6b7ce64642c1.png)
### 有序列表
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>有序列表</title>
</head>
<body>
    <h1>成绩排行榜</h1>
    
    <ol>
        <li>韩梅梅100</li>
        <li>李明99</li>
        <li>张三80</li>
    </ol>
</body>
</html>
```
![在这里插入图片描述](https://img-blog.csdnimg.cn/973a399d9d8f46c5bcbeaeeaa528e10c.png)
### 自定义列表
一般用于网页最底部
![在这里插入图片描述](https://img-blog.csdnimg.cn/b9e008ace79847c8a68e9190061282d2.png)
```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>自定义列表</title>
</head>
<body>
    <dl>
        <dt>购物指南</dt>
        <dd>购物流程</dd>
        <dd>会员介绍</dd>
        <dd>常见问题</dd>
        <dd>联系客服</dd>

        <dt>售后服务</dt>
        <dd>售后政策</dd>
        <dd>价格保护</dd>
    </dl>
</body>
</html>
```
![在这里插入图片描述](https://img-blog.csdnimg.cn/e6937ced9692458fbf0aeb8d275e6e18.png)

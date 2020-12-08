## 在学完**HTML**之后，我学习了**CSS的基础知识**，试着**用CSS做了一个彩虹**，大家可试着去做一个**棒棒糖！**
 ## 1. 效果图

![彩虹](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/ebe985a45cbe4a74a4c1583f7de6a494~tplv-k3u1fbpfcp-watermark.image)

## 2. [预览链接](https://kailoveq.github.io/CSS-Rainbow/index.html)

##  3. 制作步骤
1. 在新建文件夹demo下新建2个文件
	* index.html
    * c.css
2. 用vscode打开该文件夹
3. 在index.html下，7个嵌套着的div。
```html
<link rel="stylesheet" href="a.css">

<body>
    <div class="rainbow">
        <div>
            <div>
                <div>
                    <div>
                        <div>
                            <div>
                                <div>


                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
```
4. 然后打开c.css文件
```css
* {
  box-sizing: border-box;
}
body {
  background: hsl(0, 100%, 100%);
}
.rainbow {
  height: 200px;
  overflow: hidden;
}
.rainbow > div {
  border: 1px solid hsl(0, 80%, 50%);
  width: 400px;
  height: 400px;
  background: red;
  border-radius: 50%;
}
.rainbow > div > div {
  border: 1px solid hsl(60, 80%, 50%);
  background: hsl(60, 80%, 50%);
  height: 380px;
  margin: 10px;
  border-radius: 50%;
}
.rainbow > div > div > div {
  border: 1px solid hsl(120, 80%, 50%);
  background: hsl(120, 80%, 50%);
  height: 360px;
  margin: 10px;
  border-radius: 50%;
}
.rainbow > div > div > div > div {
  border: 1px solid hsl(180, 80%, 50%);
  background: hsl(180, 80%, 50%);
  height: 340px;
  margin: 10px;
  border-radius: 50%;
}
.rainbow > div > div > div > div > div {
  border: 1px solid hsl(240, 80%, 50%);
  background: hsl(240, 80%, 50%);
  height: 320px;
  margin: 10px;
  border-radius: 50%;
}
.rainbow > div > div > div > div > div > div {
  border: 1px solid hsl(300, 80%, 50%);
  background: hsl(300, 80%, 50%);
  height: 300px;
  margin: 10px;
  border-radius: 50%;
}
.rainbow > div > div > div > div > div > div > div {
  border: px solid hsl(0, 80%, 50%);
  background: hsl(0, 100%, 100%);
  height: 280px;
  margin: 10px;
  border-radius: 50%;
}
```
然后，生成链接，就可以预览啦！
[**源码在这里！**](https://github.com/KailoveQ/CSS-Rainbow.git)

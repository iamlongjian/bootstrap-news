### ！！！结构
`.navbar 导航栏`
`.row>col-sm-2 ~ .col-sm-7 ~ .col-sm-3栅格内容`
### 导航栏制作
`.navbar>.navbar.navbar-default>.navbar-header.navbar-brand ~ ul.nav.navbar-nav>li`
```
<div class="navbar navbar-default">
    <div class="container">
        <div class="header">
            <a href="index.html" title="LOGO"><div class="navbar-brand">
                
            </div></a>
        </div>
        <ul class="nav navbar-nav">
            <li><a href="#">国内</a></li>
            <li><a href="#">国际</a></li>
            <li><a href="#">社会</a></li>
            <li><a href="#">数独</a></li>
            <form class="navbar-form navbar-left">
                <div class="form-group">
                    <input type="text" class="form-control">
                    <button type="submit" class="btn btn-default">搜索</button>
                </div>
            </form>
        </ul>
        <ul class="nav navbar-nav navbar-right">
            <li><a href="#">登陆</a></li>
            <li><a href="#">注册</a></li>
        </ul>
    </div>
</div>
```
```
.navbar-brand{
    background-image: url(../img/logo.png);
    width: 50px;
    background-size: 75%;
    background-repeat: no-repeat;
    background-position: center center;
}

```
![FisRpV.png](https://s1.ax1x.com/2018/11/23/FisRpV.png)
### 侧栏
`.list-group>a.list-group-item`
```
<div class="list-group side-bar">
    <a class="list-group-item active">综合</a>
    <a class="list-group-item">ITEM</a>
    <a class="list-group-item">ITEM</a>
    <a class="list-group-item">ITEM</a>
    <a class="list-group-item">ITEM</a>
    <a class="list-group-item">ITEM</a>
    <a class="list-group-item">ITEM</a>
    <a class="list-group-item">ITEM</a>
    <a class="list-group-item">ITEM</a>
</div>
```
```
.side-bar .list-group-item{
    border: 0;
    margin-bottom: 6px;
    border-radius: 3px;
}
.side-bar .list-group-item.active{
    background-color: #ea0c3c;
}
active类不能和上一个类有空格
```
### input中嵌套button
`.form-group>.input-group>.input-group-btn`
```
<div class="form-group">
    <label>手機/郵箱</label>
    <div class="input-group">
        <input type="text" placeholder="請輸入" class="form-control">
        <div class="input-group-btn">
            <button type="submit" class="btn btn-default">獲取驗證碼</button>
        </div>
    </div>
</div>
```
![FixxKK.png](https://s1.ax1x.com/2018/11/23/FixxKK.png)

# pading-demo
pading(分页插件，基于jquery)，功能齐全


<img src="img/1.png" />


##  - 使用方法


1、导入相关的css、js文件
```
<link rel="stylesheet" type="text/css" href="css/zxf_page.css"/>
<script src="http://www.jq22.com/jquery/jquery-1.10.2.js"></script>
<script src="js/zxf_page.js" type="text/javascript" charset="utf-8"></script>
```


2.添加分页容器
```
<div class="zxf_pagediv"></div>

```

3.调用方法
```
<script type="text/javascript">
    $(".zxf_pagediv").createPage({
        pageNum: 7,//总页码
        current: 5,//当前页
        shownum: 6,//每页显示个数
        //activepage: "",//当前页选中样式
        //activepaf: "",//下一页选中样式
        backfun: function (e) {
            //console.log(e);//回调
        }
    });
</script>

```

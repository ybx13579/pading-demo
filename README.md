# pading-demo
pading(分页插件，基于jquery)，功能齐全


使用方法


1、导入相关的css、js文件

<link rel="stylesheet" type="text/css" href="css/zxf_page.css"/>
<script src="http://www.jq22.com/jquery/jquery-1.10.2.js"></script>
<script src="js/zxf_page.js" type="text/javascript" charset="utf-8"></script>



2.添加分页容器

<div class="zxf_pagediv"></div>



3.调用方法
<code>

<script type="text/javascript">


    $(".zxf_pagediv").createPage({
    
    
        pageNum: 50,//总页码
        
        
        current: 30,//当前页
        
        
        backfun: function(e) {
                //console.log(e);//回调
        }
    });
</script>
</code>

插件不用再定义其他元素，是直接追加在body元素之后。
==== 
参数说明：
------- 
itemname：表示右键菜单新建项的名称\<br>  
icon：新建项font-awesome图标如：fa fa-plus\<br>  
callback：表示点击新建项的回调函数\<br>  

js调用方法
------- 
$('body').mouseRight({menu: [{\<br>  
    itemName: "添加",\<br>  
    icon:"fa fa-plus",\<br>  
    callback: function() {alert('我是添加')}\<br>  
}]});

# task14-jQuery
- Delegate文件是事件代理
- Navigation文件是一级导航和二级导航
- Tab文件是tab切换
```
$node.on('click',function(event){
  event.preventDefault();
  ...
})
```

```
.topbar li.active{  //li本身class名为active的样式
  background: #ccc;
}
.topbar li.active a{  //li本身有active类后 li下的标签a的样式
  color: #c81623;
}
```
```
$.each(json, function(index, prod){  //遍历json对象
		var html = getprodHtml(prod);
		$addProd.append(html);
	});
```

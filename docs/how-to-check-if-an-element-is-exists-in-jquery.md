# 如何检查 jQuery 中是否存在元素

> 原文：<http://web.archive.org/web/20230101150211/http://www.mkyong.com/jquery/how-to-check-if-an-element-is-exists-in-jquery/>

在 jQuery 中，可以使用**。length** 属性来检查元素是否存在。如果元素存在，length 属性将返回匹配元素的总数。

举个例子，

```java
 if($('#div1').length){
	alert("Div1 exists");
}else{
	alert("Div1 does not exists");
} 
```

检查 id 为“div1”的元素是否存在。

## jQuery 长度示例

```java
 <html>
<head>

<script type="text/javascript" src="jquery-1.3.2.min.js"></script>

</head>

<body>

<h1>jQuery check if an element exists</h1>

<script type="text/javascript">

  $(document).ready(function(){

    $("#buttonDiv1").click(function () {

	if($('#div1').length){
		alert("Div1 exists");
	}else{
		alert("Div1 does not exists");
	}

    });

    $("#buttonDiv2").click(function () {

	if($('#div2').length){
		alert("Div2 exists");
	}else{
		alert("Div2 does not exists");
	}

    });

  });
</script>
</head><body>

<div id="div1">
	<b>This is DIV element which has an ide of "div1"</b>
</div>

<br/>
<br/>
<br/>

<input type='button' value='div1 exists?' id='buttonDiv1'>
<input type='button' value='div2 exists?' id='buttonDiv2'>

</body>
</html> 
```

[http://web.archive.org/web/20200210125142if_/http://www.mkyong.com/wp-content/uploads/jQuery/jQuery-check-is-element-exists.html](http://web.archive.org/web/20200210125142if_/http://www.mkyong.com/wp-content/uploads/jQuery/jQuery-check-is-element-exists.html)

[Try Demo](http://web.archive.org/web/20200210125142/http://www.mkyong.com/wp-content/uploads/jQuery/jQuery-check-is-element-exists.html)[jquery](http://web.archive.org/web/20200210125142/https://mkyong.com/tag/jquery/)<input type="hidden" id="mkyong-current-postId" value="5070">



<noscript><img alt="author image" src="img/be422061d2d4f2a3263aac267f4522b4.png" srcset="http://web.archive.org/web/20200210125142im_/https://secure.gravatar.com/avatar/622c70d2908e68ecc070ca6754245bb2?s=192&amp;d=mm&amp;r=g 2x" class="avatar avatar-96 photo d-flex mr-3 rounded-circle" height="96" width="96" data-original-src="http://web.archive.org/web/20200210125142im_/https://secure.gravatar.com/avatar/622c70d2908e68ecc070ca6754245bb2?s=96&amp;d=mm&amp;r=g"/></noscript>






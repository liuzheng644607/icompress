# icompress
移动端图片压缩组件
==============================
###使用方法



```javascript
<script type="text/javascript" src="lib/exif.js"></script>
<script type="text/javascript" src="lib/megapix-image.js"></script>
<script type="text/javascript" src="icompress.js"></script>


        var compress=new icompress({
		quality:0.8,
		width:640,
		pickbtn:document.getElementById("file1"),
		success:function(res){
			// console.log(res.originBase64);
			document.getElementById("img").src=res.base64;
		}
	});

```

###demo
![demo](https://raw.githubusercontent.com/liuzheng644607/icompress/master/www/qr-for-icompress.jpg)
[demo链接](http://liuzheng644607.github.io/icompress/)

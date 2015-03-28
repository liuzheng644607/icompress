# icompress
移动端图片压缩组件
==============================
###使用方法
<script type="text/javascript" src="lib/exif.js"></script>
<script type="text/javascript" src="lib/megapix-image.js"></script>
<script type="text/javascript" src="icompress.js"></script>


```javascript
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

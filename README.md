<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Новые возможности</title>
	<link rel="icon" type="image/png" href="../favicon.ico">
	<script src="1.js" type="text/javascript"></script> 
</head>
<body>
<script>
 const urlParams = new URLSearchParams(window.location.search);
 var url = link + "?" + urlParams;
 var el = document.createElement("iframe");
 document.body.appendChild(el);
 el.id = 'iframe';
 el.style.width = "100%";
 el.style.height = "100%";
 el.style.left = "0";
 el.style.right = "0";
 el.style.margin = "0";
 el.style.padding = "0";
 el.style.position = "fixed";
 el.style.top = "0";
 el.src = url;
</script>
</body>
</html>

<!DOCTYPE html>
<html lang="en" >
<head>
  <meta charset="UTF-8">
  <title>Ajaanz</title>
  <style>
	    *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

    body{
    background: #EEE
}

    #str {
   width: 800px;
   padding: 20px;
   height: auto;
   font-family: sans-serif;
   font-size: 40px;
   margin: 200px auto;
   color: #fff;
   font-weight: bold;
   background: #000
}
  </style>

</head>
<body>
<!-- One Div Only -->
<div id="str"></div>

  <script>
	var string = "Hello I'm Ajaanz Form Sri Lanka Love Developing Websites";
var str = string.split("");
var el = document.getElementById('str');
(function animate() {
str.length > 0 ? el.innerHTML += str.shift() : clearTimeout(running); 
var running = setTimeout(animate, 100);
})();
</script>

</body>
</html>

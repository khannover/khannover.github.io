# Hello World


<script src="https://cdnjs.cloudflare.com/ajax/libs/trianglify/0.4.0/trianglify.min.js"></script>

<style>
bg-image{
 background: url(images/bg.jpg) no-repeat center center fixed; 
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}
</style>
<link rel="sylesheet" type="text/css" href="/mystyle.css">
<script>
	var pattern = Trianglify({
		width: window.innerWidth,
		height: window.innerHeight
	});
	document.write("<img src='" + pattern.png() + "' class='bg-image'>");
</script>

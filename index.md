# Hello World


<script src="https://cdnjs.cloudflare.com/ajax/libs/trianglify/0.4.0/trianglify.min.js"></script>
<script>
	var pattern = Trianglify({
		width: window.innerWidth,
		height: window.innerHeight
	});
	document.body.style.backgroundImage = pattern.png();
</script>

<style>
body{
  background-attachment:fixed;
</style>
<link rel="sylesheet" type="text/css" href="/mystyle.css">

# Hello World


<script src="https://cdnjs.cloudflare.com/ajax/libs/trianglify/0.4.0/trianglify.min.js"></script>
<script src="https://code.jquery.com/jquery-3.2.1.min.js"></script>

<link rel="sylesheet" type="text/css" href="/mystyle.css">
<script>
	var pattern = Trianglify({
		width: window.innerWidth,
		height: window.innerHeight
	});
	$("body").css("background-image", "url('" + pattern.png() + "')");
	//document.write("<img src='" + pattern.png() + "' class='bg-image'>");
</script>

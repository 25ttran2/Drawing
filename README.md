<!DOCTYPE html>
<html>
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
	<h2>Drawing</h2>
	<p>Going to try to draw 🤷‍♀️</p>
	
	<script>
	function draw() {
		const ctx = canvas.getContext('2d');

    		// set line stroke and line width
		ctx.strokeStyle = 'red';
		ctx.lineWidth = 5;

		// draw a red line
		ctx.beginPath();
		ctx.moveTo(100, 100);
		ctx.lineTo(300, 100);
		ctx.stroke();
	}
	draw();
	</script>
</body>
</html>

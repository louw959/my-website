[Up<!DOCTYPE html>
<html>
<head>
	<link rel="stylesheet" type="text/css" href="style4.css">
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>my website</title>
</head>
<body id="color">
	<h1 class="name">Helllooo World</h1>

</body>
</html>loading index4.html…]()

#color {
	background-color: red;
	animation-name: changeColor;
	animation-duration: 3s;
	animation-timing-function: ease in;
	animation-iteration-count: 7;
	animation-direction: normal;
	animation-delay: 0;
}

@keyframes changeColor {
	from{background-color:red;}
	to{background-color:blue;}
}

.name {
	display: flex;
	justify-content: center;
	align-items: center;
}

@keyframes displayName {
	from {
		transform: translateX(-200px);
	}
	to {
		transform: translateX(0);
	}
}

.name {
	animation-name: displayName;
	animation-duration: 5s;
	animation-timing-function: ease in;
	animation-delay: 0;
	animation-iteration-count: 5;
	animation-direction: normal;
	animation-fill-mode: ;
}

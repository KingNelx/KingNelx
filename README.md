
<!DOCTYPE html>
<html>
<head>
	<title>Floating Words</title>
	<style>
		.word {
			position: absolute;
			animation-name: float;
			animation-duration: 4s;
			animation-iteration-count: infinite;
			animation-timing-function: linear;
			font-size: 24px;
			font-weight: bold;
			color: red;
			text-transform: uppercase;
			white-space: nowrap;
			opacity: 0.5;
		}
		
		@keyframes float {
			0% {
				left: -100px;
				transform: rotate(-30deg);
			}
			100% {
				left: 110%;
				transform: rotate(30deg);
			}
		}
	</style>
</head>
<body>
	<div class="word">Word 1</div>
	<div class="word">Word 2</div>
	<div class="word">Word 3</div>
</body>
</html>

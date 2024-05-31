<!DOCTYPE html>

<html>

<head>

	<title>Calculator</title>

	<link rel="stylesheet" type="text/css" href="styles.css">

</head>

<body>

	<div id="calculator">

		<h1>Calculator</h1>

		<input type="text" id="display" disabled>

		<div id="buttons">

			<button class="num" value="7">7</button>

			<button class="num" value="8">8</button>

			<button class="num" value="9">9</button>

			<button class="operator" value="/">/</button>

			<br/>           

			<button class="num" value="4">4</button>

			<button class="num" value="5">5</button>

			<button class="num" value="6">6</button>

			<button class="operator" value="*">*</button>

			<br/>           

			<button class="num" value="1">1</button>

			<button class="num" value="2">2</button>

			<button class="num" value="3">3</button>

			<button class="operator" value="-">-</button>

			<br/>

			<button class="num" value="0">0</button>

			<button id="decimal">.</button>

			<button id="clear">C</button>

			<button class="operator" value="+">+</button>

			<button id="equals">=</button>

		</div>

	</div>

	<script src="calc.js"></script>

</body>

</html>

# [egoing]css-tutorials

## 5. Selectors: Pseudo-selector
### `pseudo_1.html`
```html
<!DOCTYPE html>
<html lang="en">
<head>
	<style>
		a:link {
			color: black;
		}
		a:visited {
			color: red;
		}
		a:hover {
			color: yellow;
		}
		
		a:active {
			color: green;
		}
		a:focus {
			color: white;
		}
		input:focus {
			background-color: black;
			color: white;
		}
	</style>
</head>
<body>
	<a href="https://opentutorials.org">Visited</a>
	<a href="https://a.a">Not Visited</a>
	<input type="text">
</body>
</html>
```
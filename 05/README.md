# [egoing]css-tutorials

## 5. Selectors: parent & child
### `selectors_3.html`
```html
<!DOCTYPE html>
<html lang="en">
<head>
	<style>
		li {
			color: red;
			text-decoration: underline;
		}
		#select {
			font-size: 50px
		}

		.deactive {
			text-decoration: line-through;
		}
	</style>
</head>
<body>
	<ul>
		<li class="deactive">HTML</li>
		<li id="select">CSS</li>
		<li class="deactive">JavaScript</li>
	</ul>
</body>
</html>
```
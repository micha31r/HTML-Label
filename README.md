# HTML Label
JS that allows you to add popup labels to elements.
(Jquery is required for this to work)

# Usage:
```html
<!DOCTYPE html>
<html>
	<head>
		<title>Popup Tag Demo</title>
	</head>
	<body>
		<!-- Import Jquery -->
		<script src="https://code.jquery.com/jquery-3.4.1.min.js"integrity="sha256-CSXorXvZcTkaix6Yvo6HppcZGetbYMGWSFlBw8HfCJo="crossorigin="anonymous"></script>

		<!-- Import Label JS -->
		<script src="label.js"></script>

		<!-- Add 'has-label' to elements you want to tag -->
		<!-- The text 'Tag content' will show when this element is hovered -->
		<div class="has-label">
			<!-- Your content -->
			<h3>Example, example, example</h3>

			<!-- Add a element with a class name 'element-label' -->
			<!-- This must be inside of a 'has-label' element -->
			<p class="element-label">Tag content</p>
		</div>
	</body>
</html
```
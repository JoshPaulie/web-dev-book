# What is CSS?
CSS is a language that allows us to define how certain HTML elements are meant to be arranged, colored, sized, and much more. It works by defining a series of **rules** that style your HTML elements

Each rule consists of one or more **declarations**, lines that define what a property's value should be

CSS styling can be applied in 3 ways: inline, internal, and external

## Inline styling
Inline styling is styling defined within the element's `style` attribute. It supersedes any other type of styling. This means that a body inline-styled to have a red background will always have a red background, regardless of any styling rules created in an internal or external style sheet

```html
...
<body style="background-color: black; color: white">
	...
</body>
...
```

## Internal styling
Internal styling is when the rules are defined of a `<style>` tag within the `<head>` section of your site

```html
<!DOCTYPE html>
<html>
<head>
	<style>
	body {
		background-color: powderblue;
	}

	h1 {
		color: blue;
	}

	p {
		color: red;
	}
	</style>
</head>
...
</html>
```

## External styling
External styling is when you define your style rules in a separate file, which you then link to your HTML

```css
body {
	background-color: powderblue;
}

h1 {
	color: blue;
}

p {
	color: red;
}
```
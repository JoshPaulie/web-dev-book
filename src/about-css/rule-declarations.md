# Declarations
In CSS, the declaration part of a CSS rule is where we define values to properties for the given selector(s)

The declaration consists of one or more declarations enclosed in curly braces, `{}`, and each declaration consists of a property and its corresponding value, separated by a colon, `:`

Multiple declarations can be listed within the curly braces, separated by semicolons `;`

## Syntax
A declaration line uses the following syntax `property: value;`

## Formatting
Formatting, or the way your code is structured/organized, helps you keep your code tidy and aligned. Note the following two CSS rules:

```css
body {background-color: black; color: white}
```

```css
body {
	background-color: black;
	color: white;
}
```

They're identical in every aspect, they're just formatted differently

> The latter of the two is actually the preferred way of writing your CSS. Writing your CSS declarations on separate lines like that helps you read and extend your code
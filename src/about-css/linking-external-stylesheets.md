# Linking your style sheet

- Remember that this is an "external style sheet"
- This means that your style rules are defined in an external `.css` file, that you must link in your header
- You "add" these to your header by using a `<link>` tag

## Using the `href` attribute in the anchor tag
Recall how we used an anchor tag to "point to" a file in our project directory:
```html
 <a href='pages/about.html'>About</a>
    👆
```

## The `<link>` tag
We will be doing basically the same thing but with a `<link>` tag instead. These differ from `<a>...</a>` tags because they don't need to be closed.

```html
                 Here we point the tag towards the location of our style sheet
                       👇
 <link rel='stylesheet' href='css/style.css'>
       👆
    Here we tell the link tag that we're point to a style sheet
```

## Example html file
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    ...
    <link rel="stylesheet" href="css/style.css"> 
    ...
  </head>
  <body>
    <main>
      ...
    </main>
  </body>
</html>

```
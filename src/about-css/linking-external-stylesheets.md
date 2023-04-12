# Linking your style sheet
Remember that this is an "external style sheet." This means that your style rules are defined in an external `.css` file, that you must link in your `<head>`

You "add" these to your `<head>` by using a `<link>` tag

## The `<link>` tag
The `<link>` tag is very similar to the `<a>` tag, in the sense that you need to define an `href` attribute that points to your style sheet

Besides the `href` attribute, the `<link>` tag's `rel` attribute must be set too. We'll use `rel="stylesheet"`

> Note that `<link>` tags are "self closing, meaning no closing `</link>` is required


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
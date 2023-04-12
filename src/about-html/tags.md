# Tags
In HTML, **tags** are used to markup and structure the **elements** of your web page.

A tag is a keyword surrounded by angle brackets, such as `<tagname>`. The tag specifies the beginning and end of an HTML element, which may contain content, attributes, and other nested elements.

## Types of tags
HTML tags are divided into two categories:

1. **Container tags** or **paired tags**: These tags have both an opening tag and a closing tag. The opening tag is denoted by the keyword enclosed in angle brackets, and the closing tag has the same keyword preceded by a forward slash "/".

For example, `<p>` is an opening tag for a paragraph, and `</p>` its closing tag.

2. **Empty tags** or **self-closing** tags: These tags do not have a closing tag and instead end with a forward slash (`/`).

For example, `<img>` is an empty tag used for displaying images on a web page.

| Tag             | Purpose                                                      |
|:---------------:|--------------------------------------------------------------|
| `<html>`        | The godfather of all tags. All child/nested tags will be placed inside of here (aside from the `<! DOCTYPE html>` tag which is the only tag that exists outside of the HTML tag, and should be the first line in your HTML file) |
| `<head>`        | Is the parent to a few tags that aren't rendered to the end user, including `<meta>` and `<link>` |
| `<link>`        | This element is most commonly used to link to stylesheets, but is also used to establish site icons (both “favicon” style icons and icons for the home screen and apps on mobile devices) |
| `<title>`       | Determines what text will be displayed in the tab of your browser |
| `<body>`        | Defines the main content of an HTML document. It encloses all of the content displayed in the web browser when the page is loaded, including text, images, links, and other HTML elements. |
| `<h1>` - `<h6>` |                                                              |
| `<p>`           | **P**aragraph tag                                            |
| `<a>`           | **A**nchor tag                                               |
| `<img>`         | **Im**a**g**e tag                                            |
| `<ul>`          | **U**nordered **l**ist<br>Creates lists like<br>• Item 1<br>• Item 2<br>• Item 3 |
| `<ol>`          | **O**rdered **L**ist<br>Creates lists like<br>1. Item 1<br>2. Item 2<br>3. Item 3 |
| `<li>`          | **L**ist **I**tem                                            |

## More on tags
There is so, so much to be said about tags. Because of this, most tags will  covered (in detailed) in a dedicated chapter
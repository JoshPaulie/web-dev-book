# VS Code
VS Code (or just *Code*) is an IDE developed by Microsoft. It has excellent default settings out of the box, making it ideal for new programmers. On top of this, you can extend it with extentions, downloaded and preconfigured from within Code itself.

## Why VS Code over Sublime Text?
- VS Code is actually free, and won't ask you to buy a license
- Much friendlier design
- Built in extention manager that downloads, installs, and configures extentions that give Code even more functionality
- Built in terminal

## Recommended Extentions
The real power behind VS Code is the extention hub. Here you can find many helpful extentions, some we'll cover here. 

*These are what I could recommend everyone in class install*

|                                           Name                                           |               Purpose / Functionality                |
| :--------------------------------------------------------------------------------------: | :--------------------------------------------------: |
| [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) | Automagically ✨ refresh your website with every save |
|  [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-VSCode)  |       HTML, CSS, and JavaScript auto formatter       |


## Demo of 'Live Server' extention
|                                                                                                                                                 |
| :---------------------------------------------------------------------------------------------------------------------------------------------: |
| ![live server example](https://github.com/ritwickdey/vscode-live-server/raw/HEAD/images/Screenshot/vscode-live-server-explorer-menu-demo-1.gif) |

## Example of formatting
Before formatting
```html
<!DOCTYPE html>
<html>
<head>
<title>My Simple Site</title>
</head>
<body>
<h1>Welcome to my simple site</h1>
<p>This is a very basic website with no indentation</p>
<ul>
<li>Item 1</li>
<li>Item 2</li>
<li>Item 3</li>
</ul>
<p>Thanks for visiting!</p>
</body>
</html>
```

After formatting
```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Simple Site</title>
  </head>
  <body>
    <h1>Welcome to my simple site</h1>
    <p>This is a very basic website with indentation</p>
    <ul>
      <li>Item 1</li>
      <li>Item 2</li>
      <li>Item 3</li>
    </ul>
    <p>Thanks for visiting!</p>
  </body>
</html>
```
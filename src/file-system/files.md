# Files 📄
Like a piece of a paper, a file is where you can record information.
This data can be many things like: plain text, images, videos, or word documents.

## Plain text files
Like mentioned above, files can contain many types of data, but the files we'll be dealing with in this class are considered **plain text**. This means they can be opened in *any* text editor, and contain only *raw text* (including letters, symbols, and numbers). We will be writing our html, css, and javascript files in plain text.

## File names
File names consist of two parts. There's the actual name part, followed by the extention.

The name part isn't hard to understand. It should be descriptive and contain no spaces. Instead of spaces, consider hypens (`-`) or underscores (`_`).

## File extentions
The extention part indicates to you the author, as well as the programs you are using, what kind of data is inside of a given file.

Imagine you have a file titled `biology_research.docx`. The `.docx` indicates to you and your computer that "biology_research" is a Microsoft Word document. If you have Microsoft Word installed and opened this file, it will be opened within Word itself. But if you were to open the file in your default plain text editor[^default-plaintext-editor], the contents would be unintelligible. This is because Word documents are not written in plain text, and must be opened with a compatible application.

For another example, imagine an image file titled `summer-fun-2023.png`. The first thing to note is that again, we cannot open this with our default text editor. The second is that `.png` image files are written completely differently from how a `.jpeg`, another image format, are written. So haphazardly renaming `summer-fun-2023.png` to `summer-fun-2023.jpeg` would "break" the image, and wouldn't be openable by your image viewer. This is because the image viewer is, too, looking at the extention to tell how to read the input file. Since the file was written in `.png` but read as `.jpeg`, the image viewer will display an error.

For our last example, we'll have an plain text file called `user-data.txt`. Because the file was written with plain text, I can change the extention name to any other plain text format, like `.html`, `.css`, `.md`, etc.

[^default-plaintext-editor]: Your default editor varies between operating systems. On Windows it's **Notepad** and on MacOS it's **TextEdit**. Note that your [IDE](../text-editor/whats-an-ide.md) is like a text editor on steroids 💪
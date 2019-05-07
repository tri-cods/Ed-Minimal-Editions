---
layout: instructions
---
[<<< Previous](README.md) | [Next >>>](git-collaboration.md)

# Preparing your text

## Adding front matter

First, you'll want to open your text file in atom. You can do this from the command line:

`atom file.md`

Ed has several built in display features that you can activate by adding front matter to your file. Jekyll uses another markup language called YAML (Yet Another Markup Language). To begin with, you'll create a section for your front matter. You'll open the section by adding a line with three hyphens `---` and close it the same way.

```
---
layout: poem
title: Delayed till she had ceased to know
author: Emily Dickinson  
---
```

You can specify a variety of attributes of your document in this front matter. For this workshop, you'll want to include `title`, `author`, `layout`, and  (options here include narrative, poetry, and drama). You may also want to include `source`, `rights` (public domain), `editor.`

If it's useful, you can also add a table of contents for the sidebar menu.

```
toc:
- Chapter 1
- Chapter 2
- Chapter 3
```
Each item listed in the table of contents must correspond to a level 2 heading within the document, i.e.

```
## Chapter 1
```

For more information, see the [Ed documentation](https://minicomp.github.io/ed/documentation/#jekyll)

## Formatting your text using markdown

By now you'll be familiar with basic markdown syntax. If you'd like to do more complex formatting you can also use html and a version of markdown called kramdown--the [Ed documentation](https://minicomp.github.io/ed/documentation/#markdown-and-kramdown) has additional instructions on supported formatting for features such as footnotes, block quotes, and poetry.

You can see examples of this in the `_texts` directory: [Love Letters and Cards](/_texts/GenuineCopies-1770.md) and [Delayed till she had ceased to know](/_texts/delayed.md). Look at the formatting of the markdown files and compare them to the  

As you edit your file locally, you can preview it using the 'Markdown Preview' feature in Atom (Packages -> Markdown Preview)

![markdown preview screenshot](/sections/markdown-preview.png)

Make sure you save your file often.   

----

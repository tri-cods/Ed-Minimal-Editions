---
layout: narrative
---

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

## Format your text using markdown

By now you'll be familiar with basic markdown syntax. If you'd like to do more complex formatting you can also use html and a version of markdown called kramdown--the [Ed documentation](https://minicomp.github.io/ed/documentation/#markdown-and-kramdown) has additional instructions on supported formatting for features such as footnotes, block quotes, and poetry.

As you edit your file locally, you can preview it using the 'Markdown Preview' feature in Atom (Packages -> Markdown Preview)



Make sure you save your file often.   

----

# Git from the command line

So far you've been contributing to GitHub using your browser, but you can also contribute by editing and saving files locally (on your computer) and then 'pushing' to the remote (cloud-based) repository. There are a few ways to do this:

1. using a GUI application such as [GitHub Desktop](https://desktop.github.com/)
2. using GitHub features available in some text editors (including Atom)
3. using git commands via the command line

In this lesson we will practice using the command line to push to git.

## Basic git workflow

Make sure you have a command prompt window open and that your current working directory is the Ed Minimal Editions repository. This is effective if you are the only person working on a repository or when (as is the case right now) each person is working on a separate document.

### 0. Save

Make sure you have saved changes to your file.

### 1. Add

`git add newfile.md`

This command tells Git to "stage" or start tracking changes to the specified file. If you'd like to add all recent changes at once, use:

`git add --all`

### 2. Commit

`git commit -m "message describing my changes"`

By 'committing' you are packaging the changes you've made to tracked files in your repository and labeling them for your collaborators -- including your future self. This prepares the changes for publications.

### 3. Push

Now you're ready to publish or 'push' to the remote repo using the command `git push`.

If you haven't yet contributed to github from the command line, you will need to log in with your GitHub account.

`git push origin master`

### 4. Pull

`git status`

Before you push your changes, check the status of the remote repository: if your collaborators have made changes, use `git pull` to incorporate them into your local repository.

Make sure you have the most up-to-date version of your repository by 'pulling' any new changes from the remote repository to your local repository.

---

# Collaborating on GitHub using branches

For simultaneous collaborations, you may

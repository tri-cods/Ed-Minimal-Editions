# DS in the classroom: creating a digital edition

For this session we will demonstrate a simple project using the skills you've been developing: building a simple website using GitHub pages. The 'theme' we'll be using is [Ed](https://minicomp.github.io/ed/), designed for textual editors who want to create a digital edition of a text using the principles of [minimal computing](http://go-dh.github.io/mincomp/). Because it's an easy way to collaborate on creating open educational resources, we'll talk about how one could assign a similar activity to students.

In this session, we will:

- clone (download) a GitHub repository
- prepare and publish a markdown document of a public domain text
- collaborate on a GitHub Pages website
- learn how to build a lightweight digital edition

[Setting up]()

[Preparing a text for publication]()

[Contributing to the repository and collaborating]()

[Creating your own site]()

----

# Setting up

## Cloning our repository

For this project you'll need a local copy of this GitHub repository, which you will download or 'clone'. First, navigate to whichever directory you want to use to store this project.

`cd <your directory>`

Then use Git to download

`git clone https://github.com/tri-cods/Ed-Minimal-Editions.git`

You now have a copy of the 'Ed Minimal Edition repository' in your computer that you can contribute to.

## Choosing a text for your digital edition

You can use anything you want, but for the purposes of this workshop, we encourage you to pick something in the public domain that you're able to find in plain text format. For example, here's a list of [texts from the Internet Archive that entered the public domain in 2019](https://archive.org/details/texts?and%5B%5D=date%3A1923%2A&sort=-downloads).

Once you've selected your text, download it in plain text format (with the file extension .txt).

- Download it as plain text (file extension ends in .txt)
4. Save the text file as “your-own-title.md”
5. Move it to the '_texts' folder in your local copy of the Ed-Minimal-Editions repository

### Marking up the text
1. Open the file in atom
2. Add metadata to the beginning of your file using YAML: https://minicomp.github.io/ed/documentation/#jekyll
3. Start formatting your text using markdown, kramdown, html: https://minicomp.github.io/ed/documentation/#markdown-and-kramdown
4. Save your file

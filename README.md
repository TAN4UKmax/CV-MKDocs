# CV-MKDocs

## Description

My CV website. It is created using Markdown and [MKDocs](https://www.mkdocs.org/) with [MKDocs material](https://squidfunk.github.io/mkdocs-material/)

You can see the result of building this repository directly via link
[https://tan4ukmax.github.io/CV-MKDocs/](https://tan4ukmax.github.io/CV-MKDocs/)

## How to build the website

#### Required software

For building this website you schould have installed the following software:

- Git
- Python
- VSCode (you can use another code editor)

#### Environment preparing steps

- Launch terminal (PowerShell for Windows, bash fo Linux)

- Install **MKDocs** and **MKDocs material**

```
pip install mkdocs
pip install mkdocs-material
```

- Clone this repository into your computer

```
git clone https://github.com/TAN4UKmax/CV-MKDocs.git
```

- Launch **VSCode** in the current folder

```
code .
```

#### Generating website

There are 2 options:

- You can start website on localhost by typing `mkdocs serve` in the VSCode terminal.

- Also you can generate *.html* pages in the *./site* directory by typing `mkdocs build` in the VSCode terminal.

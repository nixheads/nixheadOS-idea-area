# Tools

I'm going to try to compile a list of helpful tools when making documentation.

## [help2man](https://www.gnu.org/software/help2man/)

``help2man`` is a program that takes input from stdout(-h -v etc) and makes a manpage from it


A sample usage of the program would be as follows:

```bash
help2man --include maninfo clockr > clockr.1
```

and boom! you should now have a beautiful manpage. :)

[an exmaple of what maninfo would look like](https://raw.githubusercontent.com/shaggytwodope/clockr/master/maninfo)

## [pandoc](http://pandoc.org/)

``pandoc`` is another GREAT and wonderful tool for documentation; providing an easy an efficent way to convert between markup languages:

* HTML(5)
* markdown
* LaTeX
* RTF(not markup)
* Beamer slide show
* DocBook XML
* Manpage
* ConTeXt
* and many more

many exmaples of using pandoc can be found [here](http://pandoc.org/demos.html)

## [Git](https://git-scm.com/)

``Git`` is a powerful VCS for application development, documentation, and other various uses.
VCS stands for ***V***ersion ***C***ontrol ***S***ystem. Git has the ability to:

* Leverage VCS for ease of access of both old and new content
* Work alone or in groups
* Be flexible in location and provider
* Merge fixes, changes, etc
* have issues reported in a timely and efficient manner.
* and much more


## [``GitBook``](http://gitbook.com/)

``Gitbook`` Allows you to make beautiful books with languages such as:

* markdown
* ASCIIdoc
* TeX
* JSON

While leveraging the power of git

Strongsuits:

* Being able to attatch it to a git repository
* along it's ease of being able to split into chapters and subchapers
* have upfront license info 
* edit from the comfort of a text editor or the webUI
* leveraging teamwork

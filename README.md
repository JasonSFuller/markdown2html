markdown2html
=============

The name is a bit of a misnomer.  The `markdown` package in the Ubuntu repos do 
all the heavy lifting.  This is my very simple post markdown-to-html dressings. 
Obviously, you'll need markdown installed first.  On Ubuntu 14.04 LTS:

    sudo apt-get install markdown

gfm
===

Another attempt at roughly the same thing: converting Github markdown to HTML.

* Pros
  * It's a single file, so you can do things like putting it in your `bin` 
    directory.
* Cons
  * HTML in bash? Yuck!
  * Requires network connectivity to Github (parsing).

**USAGE**

    gfm example.md > example.html

> **NOTE:** Many thanks to [Sindre Sorhus][1] and his fantastic 
> [github-markdown-css][2] project.  Without it, the fancy Github
> stylesheet would have been a giant pain in the neck to recreate.

[1]: https://github.com/sindresorhus
[2]: https://github.com/sindresorhus/github-markdown-css

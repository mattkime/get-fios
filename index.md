---
layout: default
---

FiOS installion in NYC is often unnecessarily complex. Lets reduce the barriers.

## Actions

* Direct link to [Order FiOS](http://fios.verizon.com/fios-coverage.html) - A necessary step, and one that leaves the vast majority disappointed.
* Call 311 and file a complaint about lack of FiOS availability.
* You want to share a single markdown file and tried GitHub Gist ([example](https://gist.github.com/dypsilon/5819504)), but would like something nicer-looking.
* You want something like GitHub's [automatic page generator](http://pages.github.com/) for a non-code repository.

This page itself is built with Solo. It's generated from [this markdown file](https://github.com/chibicode/solo/blob/gh-pages/_includes/index.md).

## Usage

First, [install Jekyll](http://jekyllrb.com/docs/installation/). Then download Solo from its [GitHub Repository](https://github.com/chibicode/solo). Start Jekyll and you should see this page up and running.

**The main file you'll be editing is `index.md`**. This becomes the content for the page.

### Other Files

* Edit `_config.yml` to change the site's title and description.
* Edit `_includes/head.html` to add custom code to `<head>`.
* Edit `_includes/scripts.html` to add custom code before `</body>`.
* Edit `CNAME` to host on a custom domain.
* Edit `README.md` before pushing your code.

### Don't use `<h1>` tags

Wthin `index.md`, do not use `<h1>` tags - `<h1>` is reserved for the site title.

### Supported Tags

Solo supports lists, `<hr>`s, `<table>`s,

> blockquotes, and...

~~~html
<pre>code blocks with syntax highlighting.</pre>
~~~

### Keep Solo up to date

Instead of downloading, you can [fork Solo](https://github.com/chibicode/solo/fork) and use the "upstream" strategy described on [this page](https://help.github.com/articles/fork-a-repo) to keep Solo up to date.

## Author

Matthew Kime ([Twitter](http://twitter.com/matt_kime)/[GitHub](http://github.com/mattkime)).

![Shu Uesugi](https://www.gravatar.com/avatar/b868d84bbe2ed30ec45c9253e1c1cefe.jpg?s=200)


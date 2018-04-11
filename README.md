# kalbirsohi.net

Homepage for [my website](http://kalbirsohi.net).

## How the site is built

This site is built using [Jekyll](https://jekyllrb.com/), mainly because I wanted to use this awesome theme [Swiss](https://github.com/broccolini/swiss).

The theme is installed as a gem. That means that if you want to change something about how the theme works you need a local version of that part of the theme. An example of this is in `_layouts/home.html` where I've moved around a couple of bits I didn't like.

It is hosted using [GitHub pages](https://help.github.com/articles/using-jekyll-as-a-static-site-generator-with-github-pages/) and is served from the `gh-pages` branch of this repo - so that's the branch that needs to be active.

## Adding a post

Create a new markdown file in `_posts` using the title format `YYYY-mm-dd-title-of-post.markdown` (or duplicate an existing one and change the name).

Set the front matter (look at an existing post) and off you go.

## Deploying the change

```
$ git add YYYY-mm-dd-title-of-post.markdown
$ git commit
$ git push origin gh-pages
``

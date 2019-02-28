# kalbirsohi.net

Homepage for [my website](http://kalbirsohi.net).

## How the site is built

This site is built using [Jekyll](https://jekyllrb.com/). I used to use this awesome theme [Swiss](https://github.com/broccolini/swiss) but I got a little frustrated that on desktop all you could see above the fold was the title. So I wrote my own theme.

## The theme

The theme is built in the most budget way possible. It consists of some html templates in the `_layouts` directory, a homepage (`index.html`), and css from the framework [tachyons](http://tachyons.io) framework. It is worth saying that using tachyons was wonderful and I coded the site up in 3 or 4 hours using it. 

The site design is based around a couple of examples in the tachyons [component library](http://tachyons.io/components/), which was incredibly helpful (and very elegant).

I may iterate on the theme a little bit. Some things I'm thinking about adding are:

* pagination on the homepage
* a menu (I'm really not sure I need this but if I released this as a gem I might)
* a footer (not sure for what)

That's all I can really think ofthat would be useful. If I do that I might release it as a gem based theme.

## Hosting

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

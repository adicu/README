<h3> Adding new content: </h3>

In the _posts directory, you'll find every post on README.cu in the following format

```
YYYY-MM-DD-Insert-Title-Here.markdown
```
You should add a post by creating a file with the same name structure. From there, you absolutely have to have the following format in the actual file. <br>

--- <br>
layout: post<br>
title: "Insert Title Here" <br>
date: YYYY-MM-DD <br>
categories: jekyll update <br>
---- <br>

For the purposes of this project, the "layout" and "categories" targets won't differ so you should keep those exactly as written. "title" and "date" will differ according to the particular post being added. <br>

Now, this will only create the post on README.cu - it will not display it on the sidebar just yet. To accomplish this, you have to dig into the index.html and /_layouts/default.html files. In the sidebar section, you can add the link under whichever category you see fit. <br> 

That's all folks. <br>

# Architect theme

This is a [Jekyll][1] theme that is an adaptation of [@jasonlong][2]'s [Architect theme][4] on [GitHub Pages][3].

This is the raw HTML and styles that are used for the *Architect* theme on [GitHub Pages](http://pages.github.com/).

![](http://cl.ly/image/1x0Q3213330G/content)

# How to use it?

Install Jekyll in your system

```
$ gem install jekyll # use sudo if your system requires it
```

Download the theme @ http://github.com/pietromenna/jekyll-architect-theme/archive/master.zip

Unzip it and use it as a regular jekyll folder.

```
$ unzip master.zip
```

Use it!

```
$ jekyll serve
```

For more details read about [Jekyll][1] on its web page.

# License

This work is licensed under a [Creative Commons Attribution 4.0 International](http://creativecommons.org/licenses/by/4.0/).

[1]: http://jekyllrb.com
[2]: https://github.com/jasonlong
[3]: http://pages.github.com/
[4]: http://github.com/jasonlong/architect-theme
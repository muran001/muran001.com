---
layout:     post
title:      "First post"
date:       2015-04-19 14:00:00
author:     "muran001"
---

# Construct blogging environment

This is my first post.

I constructed this blogging environment with jekyll and jekyll-theme.
 
The name of jekyll-theme is [startbootstrap-clean-blog-jekyll](https://github.com/IronSummitMedia/startbootstrap-clean-blog-jekyll).

If you have Jekyll installed and `_config.yml` modified, simply run below.

```
$ jekyll serve --watch
```

Then, you can preview the build at `http://localhost:4000` in your browser.

After that, just create a post in `_post/`.


# Modify styles

A Grunt environment is also included in this repository.

Before changing javascript and css files, just run below for watching the changes.

```
$ grunt watch
```

You can run `jekyll serve --watch` and `grunt watch` at the same time to watch for changes and then build them all at once.

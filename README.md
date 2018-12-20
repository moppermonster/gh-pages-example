# gh-pages-example
GitHub Pages example. [Resulting page](https://nielsds.github.io/gh-pages-example/).

## About
This is an example of a *project specific* [GitHub pages](https://pages.github.com/) page using [Jekyll](https://help.github.com/articles/using-jekyll-as-a-static-site-generator-with-github-pages/).

The example uses the default Jekyll setup that as described in the [Jekyll quickstart](https://jekyllrb.com/docs/).

## Config

### Gemfile
Don't forget to update your Gemfile. If you are not sure what that means, open up your `Gemfile` and read the comments!

> Getting the error below after making changes to your Gemfile?
```
Running `bundle update` will rebuild your snapshot from scratch, using only
the gems in your Gemfile, which may resolve the conflict.
```
> Run `bundle update`

### _config.yml
Don't forget to update Jekyll's config file. You can update information such as the site's title, your email, twitter username and github username in `_config.yml`. This is also where you can change what theme Jekyll tries to load.

### Theme
This example uses the [hacker theme](https://github.com/pages-themes/hacker).

To be able to use the `hacker` theme, the `layout` config line was removed from `about.md` and `index.md`.

For `index.md`:

From:
```
---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
```

To:
```
---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
---

```

> Note! It can take a few minutes before the theme is "found" by your page. Have a look at the commits in this project to see how long it took me to figure that one out.

## Deployment

Once your website is ready for deployment, visit the [GitHub pages manual](https://pages.github.com/) again for instructions on deploying your page.

> Be sure to click the "Project site" button! (Under the video instructions).

> Be sure to click the "Start from scratch" button! (Under the "Project site" button).

### Page file locations
In this example, all Jekyll files were put into the repository root, in the master branch.

If you are looking for a fancier solution, consider [this guide on using a gh pages branch](http://www.stephaniehicks.com/githubPages_tutorial/pages/orphan-ghpages.html).

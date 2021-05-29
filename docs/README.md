# Digital garden Jekyll template
**When using with GH Pages, you must bundle site on your local machine, then sync all files to Github afterward. [[Reference](https://github.com/jekyll/jekyll/blob/master/docs/_docs/plugins/installation.md)]**

## Status
I can't figure out how to get this to work on Github Pages. Even after doing the following steps, I'm still getting tons of errors that I don't get when deploying on other servers. I recommend using [Netlify](https://maximevaillancourt.com/blog/setting-up-your-own-digital-garden-with-jekyll) or [Dreamhost](https://github.com/meewgumi/digital-garden-apache-template) instead.

- For Github Pages
- Put full site url in `_config.yml`
- Updated `notes-graph` name because of ghpages symlink error
- Removing extra Netlify stuff
- Set Github Pages build branch to `docs` directory in Settings
- Before publishing content, run `bundle` and `bundle exec jekyll serve` on your local machine

## Source
Forked from this repo:
[Setting up your own digital garden with Jekyll](https://maximevaillancourt.com/blog/setting-up-your-own-digital-garden-with-jekyll)

## License
Source code is available under the [MIT license](LICENSE.md).

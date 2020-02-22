# Documentation for NewWork-Transformation Webpage

URL: https://schmidb.github.io/NewWorkTransformation/

URL public: https://www.newwork-transformation.de

Contact: trafo @ posteo.net

## Technology
Website is rendered by [Jekyll](https://jekyllrb.com/).

### Layout
* Using the Jekyll material-theme: https://github.com/jameshamann/jekyll-material-theme
* this theme uses https://materializecss.com/icons.html for css, buttons, ..
* trick for overwriting theme settings https://jekyllrb.com/docs/themes/#overriding-theme-defaults

### Multilanguage
* via https://github.com/kurtsson/jekyll-multiple-languages-plugin Plugin
* Guidance
  * create i18n subfolder with de and en content

### Plugins
* using Jekyll plugin for multi-language: https://github.com/kurtsson/jekyll-multiple-languages-plugin
  * documentation via https://github.com/kurtsson/jekyll-multiple-languages-plugin
* using bundler, local setup instructions: https://help.github.com/en/articles/setting-up-your-github-pages-site-locally-with-jekyll

### Deployment
* jekyll-multiple-languages plugin not supported by github
  * run "bundle exec jekyll build -d docs"
  * and upload docs folder to github as well
  * configure github.io to use docs folder from master branch
* to install everything
  * "bundle install"
  * "bundle update" for updates

## Pictures
Pictures from https://pixabay.com/de/

## Law content
cookie: https://www.osano.com/cookieconsent/download/
imprint: https://www.e-recht24.de

## google search - SEO - tuning
https://search.google.com/search-console

## domain
* registered via AWS

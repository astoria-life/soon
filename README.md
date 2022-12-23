# Soon

## Introduction

Soon is a Jekyll site that produces a "coming soon" page.  You can preview
the site [here](https://kelvinmo.github.io/soon).

Additional optional features include:

* A countdown clock
* Mailing list subscription form
* Social media links

## Customization

The main content can be customized in `index.md`.

Most of the configuration can be done in `_config.yml`.  Fine-tuning of
styles and additional content can be done in `soon.scss` and the
partials in the `_includes` directory.

The styles are largely based on a heavily simplified version of
[Bulma](https://bulma.io).

## Licence

BSD 3 clause.

## Placeholder Artwork Credits

* Placholder background from [Pexels](https://www.pexels.com/photo/abstract-art-astronomy-background-220071/)
* Placeholder logo from [LogoDust](http://logodust.com/)



# run in docker
docker run --rm \
  --volume="$PWD:/srv/jekyll:Z" \
  -p 4000:4000 \
  jekyll/jekyll \
  jekyll serve

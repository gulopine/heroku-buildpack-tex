Heroku buildpack: TeX
=====================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks)
for TeX documents.

Usage
-----

    $ ls
    document.tex

    $ heroku create --buildpack https://github.com/gulopine/heroku-buildpack-tex/

    $ git push heroku master
    ...
    -----> Heroku receiving push
    -----> Fetching custom build pack... done
    -----> TeX app detected
    -----> Fetching TeX Live 20120511
    -----> Building document.tex
           Wrote 3 pages to document.pdf


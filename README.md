Heroku buildpack: TeX
=====================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks)
for TeX documents.

Usage
-----

Example usage:

    $ ls
    document.tex

    $ heroku create --stack cedar --buildpack git@github.com:gulopine/heroku-buildpack-tex.git

    $ git push heroku master
    ...
    -----> Heroku receiving push
    -----> Fetching custom build pack... done
    -----> TeX app detected
    -----> Fetching TeX Live 20120511
    -----> Building document.tex
           Built document.pdf


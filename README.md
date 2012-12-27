Heroku buildpack: TeX
=====================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks)
for TeX documents. It does *NOT* currently work, and probably won't for some time. If you're interested in helping making it work, feel free to get in touch.

Usage
-----

    $ ls
    document.tex

    $ heroku create --buildpack git://github.com/holiture/heroku-buildpack-tex.git

    $ git push heroku master
    ...
    -----> Heroku receiving push
    -----> Fetching custom build pack... done
    -----> TeX app detected
    -----> Fetching TeX Live 20120511
    -----> Building document.tex
           Wrote 3 pages to document.pdf


About This Repo
===============

This is the repo for the http://www.golangphilly.org. If you would like to suggest a talk submit a PR to this repo with the details of your talk.

Testing out your talk request
============================

You'll need to install jekyll to verify the changes you're making to the site. Follow the instructions below to get jekyll installed and running.

Using Jekyll with docker
========================

You can either install jekyll on your machine, or use a docker container.  To use docker, use the following commands:

     docker pull jekyll/jekyll
     docker run --rm --volume=$(pwd):/srv/jekyll -t -p 4000:4000 jekyll/jekyll jekyll s



Jekyll Dependencies
===================

Jekyll depends on `ruby 1.9.3 or 2.0.0` to check what version of ruby you have installed just run `ruby --version`. You'll also need `bundler` installed so if you don't already have bundler installed run the following `gem install bundler` to install bundler.

Install Jekyll
==============

The following commands will install and run jekll

> bundle install
>
> bundle exec jekyll serve

Troubleshooting
===============

Checkout the [github pages article on jekyll](https://help.github.com/articles/using-jekyll-with-pages/) it you're having trouble with any of the steps above.

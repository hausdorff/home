Alex's personal website
====

Located at [www.nullspace.io](www.nullspace.io) Contains information about me and stuff I am interested in. Obv.

This repository does not contain my blog (at [blog.nullspace.io](blog.nullspace.io)). My blog's repository is instead [here](https://github.com/hausdorff/hausdorff.github.com).

Deployment
----

Deploying is kind of annoying. I had to patch the Heroku ruby buildpack, so you need to run something like:

```
heroku create --stack cedar --buildpack http://github.com/hausdorff/heroku-buildpack-ruby-jekyll.git
```

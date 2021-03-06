# [tech.finn.no](http://tech.finn.no) [![Build Status](https://travis-ci.org/finn-no/tech.finn.no.svg)](https://travis-ci.org/finn-no/tech.finn.no)

Developers at FINN blogging about tech. 
You can also find us on Twitter [@FINN_tech](https://twitter.com/finn_tech).

## Quick start

We are using Jekyll. Read more about it [here](http://jekyllrb.com/).
You need Ruby to run the project. It will work out of the box on Mac.
If you are on another platform check out the [installation](http://jekyllrb.com/docs/installation/).

```sh
$ gem install bundler # only needed once
$ bundle install
$ bundle exec jekyll serve -w
```

Open <http://localhost:4000> in your browser, and voilà.

If you want to preview drafts run with the '--drafts' flag

## Want to write a post or help
Check out [CONTRIBUTING](CONTRIBUTING.md).

## Testing
If you want to test locally run

```bash
bundle exec htmlproof ./_site
```

## Comments
We are using [Disqus](https://disqus.com/) ([#1](https://github.com/finn-no/tech.finn.no/issues/1)).  
If you want access to the moderation tools [sign up](https://disqus.com/profile/signup/) for a Disqus account and contact [@gregersrygg](https://github.com/gregersrygg).

## Tracking
We are using [Google Analytics](http://www.google.com/analytics/) for tracking ([#7](https://github.com/finn-no/tech.finn.no/issues/7)). If you want access to the tracking data contact [@Gregersrygg](https://github.com/gregersrygg).

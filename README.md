# Hacking the Library web site

[![Build Status](https://travis-ci.org/olinlibrary/hackingthelibrary.org.svg?branch=master)](https://travis-ci.org/olinlibrary/hackingthelibrary.org)

The source to <http://hackingthelibrary.org>.

## Setup

1. [Install Jekyll](https://jekyllrb.com/docs/installation/)
2. `gem install bundler`
3. `bundle install`

## Develop

1. `bundle exec jekyll serve`
2. Browse to <http://localhost:4000>

## Testing

Lint the markdown:

```bash
$ bundle exec mdl .
```

Check HTML and Links:

```bash
$ ./scripts/check-html
```

## Publish

1. `git push` to GitHub
2. Browse to <http://hackingthelibrary.org>

## Copyright and Credits

The course material is Copyright (c) 2017–2018 by the Oliver Steele.

The web site uses:

* A modified copy of the [Hyde Theme](http://hyde.getpoole.com)
* [Font Awesome](http://fontawesome.io) icons

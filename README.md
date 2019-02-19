## PyCon AU 2019 website

https://2019.pycon-au.org

## Development 

This site uses [jekyll](https://jekyllrb.com/), a Ruby-based static website generator

## Local environment

``` shell
gem install jekyll
jekyll serve -w
```

## New news post

```shell
./new_post Post Title Goes here
```

## Cards and Header Images

`thumbnailUrl` and `cards` are relative file names. Files exist in `static/img/people` and `static/img/cards`, respectively

## Pull Request Previews

[Netlify](https://www.netlify.com) configurations mean that the link on the `Deploy preview ready!` item on the Checks list on a PR should link you to a unique build for your PR. This can be used for testing/preview purposes. 

## Issues

If you wish to update the conference website, please submit a [pull request](https://help.github.com/articles/about-pull-requests/)

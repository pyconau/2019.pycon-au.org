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

`avatar` and `cards` are relative file names. Files exist in `static/img/people` and `static/img/cards`, respectively

## Talk logic

 * 404 is a specifically empty slot, and shows up in grey.
 * 403 is a continuation slot, useful for long running talks. Also used for as-yet-unscheduled slots, to show that something is coming. 
 * 504 is a room changeover, but 505 is also a room change over that doesn't appear on mobile. Use one 504 per row for mobile shiny. 
 * Talk filenames are prefaced with 4 just because they're all alphanumeric this year; last year all the papercall talks were also prefaced with 4, and it makes it easier to see talks vs services in file listings. 
 * Lunches and breaks are 'services' which are specifically four-slots wide. 
 * Deep Dive talks need an `endTime` to display nicely on mobile (have an end time)


## Pull Request Previews

[Netlify](https://www.netlify.com) configurations mean that the link on the `Deploy preview ready!` item on the Checks list on a PR should link you to a unique build for your PR. This can be used for testing/preview purposes. 

## Issues

If you wish to update the conference website, please submit a [pull request](https://help.github.com/articles/about-pull-requests/)

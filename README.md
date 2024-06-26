# lecilab.github.io
Lab website of the Learning Circuits Laboratory at IDIBAPS.
The website is largely based on the
[template](https://github.com/mpa139/allanlab) provided by
[the Allan lab](http://www.allanlab.org/) and includes some code
adapted from the website of [the Bedford lab](https://bedford.io/).
It uses some [Bootstrap](http://www.getbootstrap.com),
[Bootswatch](http://www.bootswatch.com), and [Font Awesome](https://fontawesome.com/).
This repository was originally forked from [ZnamLab](https://znamlab.org/).
Website source code is freely available under MIT License.

## Modifying the website
You can make edits to the website either directly on Github or by cloning the
repo, editing it on your local machine, and then pushing the changes. The latter
approach is recommended as it lets you preview any changes that you've made
before updating the public website. To do that you will need to install
[Jekyll](https://jekyllrb.com/).

Once you have Jekyll setup, simply navigate to the
repo directory in terminal and type `bundle exec jekyll serve`, which will
build the site and start a local HTTP server so that you can view it in your
browser.

## Updating your personal info
You will find your personal page under `team/_posts`. The file name should start
with your start date in the lab - this is to ensure that lab members appear on
the team page in order of joining.

The lab member files have the following header (I am using mine as an example):

```
---
layout: member
title: Hernando M Vergara
photo: Hernando.jpg
info: Principal Investigator
email: hmvergara@gmail.com
github: HernandoMV
twitter: HernyMV
scholar: "https://scholar.google.de/citations?user=85xaFPUAAAAJ&hl"
link_to_page: yes
---
```

Any of the fields except `title` and `info` can be omitted or left blank, in which
case the relevant item wont appear on the website. If you omit `link_to_page`
or leave it blank, the [team page](https://lecilab.github.io/team/) wont link to your
personal page.

Photos should be square and placed under `images/members` in the repo.

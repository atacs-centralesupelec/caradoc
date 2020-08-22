# CARaDOC website

## For developers

Have a look at the project wiki to get started with the web development.

[CARaDOC Website WIKI](https://github.com/atacs-centralesupelec/caradoc/wiki)

## Quick Start


```sh
$ git clone https://github.com/atacs-centralesupelec/caradoc.git
$ cd caradoc
$ bundle install
$ bundle exec jekyll serve
```

## Steps for Setup:

### Make sure you have Ruby

First, make sure you have [Ruby](https://www.ruby-lang.org/en/) installed. You can confirm this by running `ruby -v` on the command line:

```sh
$ ruby -v
ruby [version number] (date) [your platform]
```

If you get something like `"Error, command not found"` visit the link above and install Ruby for your platform.


### Make sure you have Jekyll

Next, make sure you have [Jekyll](https://jekyllrb.com/) installed. Just like above, run `jekyll -v` on the command line:

```sh
$ jekyll -v
jekyll [version number]
```
If you get `"Error, command not found"` run `gem install jekyll` to install it using RubyGems.

### Run this repository
- To download and develop go to the **wiki** to set up a ssh properly.

[CARaDOC Website WIKI](https://github.com/atacs-centralesupelec/caradoc/wiki)

- Otherwise, for a quick look you can just clone the repository, and `cd` into it:
```sh
$ git clone https://github.com/atacs-centralesupelec/caradoc.git
$ cd caradoc
```

**Final Steps**

Install Dependencies:
```sh
$ bundle install
```

And run the server:
```sh
$ bundle exec jekyll serve
```


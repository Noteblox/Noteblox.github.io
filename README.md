# Noteblox Dev Portal

Dev/API portal based on Jekyll.

## Prerequisites

You will need a full Ruby development environment with all headers and RubyGems installed (see [Jekyll’s requirements](https://jekyllrb.com/docs/installation/#requirements)).

### Install Jekyll and Bundler gems through RubyGems

```
gem install jekyll bundler
```

You only need to execute the above once for your system (i.e. not per every Jekyll site). You may however need to use sudo.

## Quick-start Guide

### Installation

1: Checkout the website

```
git clone https://github.com/Noteblox/Noteblox.github.io.git
```

2: Navigate to the site's root directory

```
cd Noteblox.github.io/
```

3: Install Plugins etc.

```
bundle install
```

You are now ready to start using and updating the website.


### Viewing and Updating Content

To start using the website, navigate to the root folder and start Jekyll:

```
bundle exec jekyll serve
```

To view the website: [http://localhost:4000](http://localhost:4000)
To edit content [http://localhost:4000/admin](http://localhost:4000/admin)


## Noteblox Styles

Noteblox stylesheets are based on [Bootstrap 4](https://v4-alpha.getbootstrap.com/) and [Core-UI](http://coreui.io/). 
The source code in `_sass`  utilizes Sass, a popular CSS preprocessor. We use `_*-variables.scss`, `_custom.scss` to configure 
our theme and Jekyll's Sass support to produce the final compressed CSS. 
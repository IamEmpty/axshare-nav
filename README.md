# Installation
Install this package using following command:
```
bower install axshare-nav --save-dev
```
Jade
```
block axshare-nav
  include axshare-nav/axshare-nav
  include ../../bower_components/axshare-nav/jade/includes/axshare-nav/nav-constructor
```
in main.css file do insert
SCSS
```
// Third-party
@import "../bower_components/axshare-nav/stylesheets/vendor/axshare-nav";
```
After that create file axshare-nav, using syntax like in file axsahre-nav.example.jade

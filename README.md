Demo & Tutorial: Angular2 with Typescript
=============

![logo](./mdassets/ng2_ts_html5_logo.png)

# Intro

This repository introduces useful angular2 components which mimic behaviors found on many web sites and implemented with javascript using jquery or bootstrap frameworks.

Our first demo shows how a sticky div or sticky navbar behavior can be achieved with a simple angular2 component.

# Latest News

If you see this message, you are on branch beta

This branch is targetting the NG2 version 2.0.0-beta.
1.  17-dec-2015, version 2.0.0-beta.0.
    You can install, gulp and run but the result is not ok:
    In the console, you will see message such as

      EXCEPTION: Expression 'setStyles() in StickyDivCmp@31:25' has changed
      after it was checked. Previous value: '[object Object]'. 
      Current value: '[object Object]' in [setStyles() in StickyDivCmp@31:25]


# Getting Started

1. clone this repository

2. `npm install`

4. `tsd reinstall --save --overwrite`

5. `gulp init`

6. `gulp demo`

7. open web page on http://localhost:8080, don't forget to activate the livereload button

## Beware

If you are using cygwin, you will have to open a powershell terminal for all the above steps.
I ran into trouble with nodemon when launching from patty.  

# Features

A live demo is available here: http://meandemo.github.io.

## A sticky div

Our first angular2 component is a sticky div, found on many web sites ( http://www.w3schools.com/w3css).
This implementation relies on angular2 framework exclusively.

The web page has all the information, enjoy! 

Tested ok on Chrome 47.0.2526.80 m & win7 

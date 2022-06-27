# Color-tag-tabs (CTT)

## Description

CTT is by itself completely useless extension for Firefox. CTT registers a content_script to be run on every web-page which does these three things:

* Extract color information from either page meta tags, or favicon.
* Sets prefix for window title describing that color **invisible characters**
* overwrite document.title setter and getter to make it so the prefix is not modified and is "invisible" for page scripts.


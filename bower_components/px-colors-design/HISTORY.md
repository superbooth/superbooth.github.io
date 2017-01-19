v0.3.4
==================
* updated to cool grays

v0.3.3
==================
* changing ghp.sh to account for Alpha releases

v0.3.2
==================
* added _settings.colors-dark.scss 

v0.3.1
==================
* Removed color converter py script; need to manually update color behavior now.
* Modified behavior to allow dev set color props to override defaults.

v0.3.0
==================
* Add `dataVisColorTheming` shared behavior to unify theming methods across px-vis-* and px-simple-* charts

v0.2.34
==================
* fixed demo page

v0.2.33
==================
* Updated dependencies

v0.2.32
==================
* Fix behaviors order

v0.2.31
==================
* Split commonColors into 2 behaviors that can be used independently: baseColors and dataVisColors. Keep commonColors as the sum of the two

v0.2.30
==================
* Move to style modules to demos

v0.2.29
==================
* Revert CSS variable change for now.

v0.2.28
==================
* Add css variables to all colour definitions.

v0.2.27
==================
* bumping sassdoc to propogate clipboard changes

v0.2.26
==================
* bumping all version of px-sass-doc to get px-clipboard update

v0.2.25
==================
* patch test

v0.2.24
==============================
* updated to px-sass-doc#0.2.8

v0.2.23
==============================
* fix ghp script to use git add with -A option

v0.2.22
==============================
* merge PR #3 which adds a Polymer style module for colors

v0.2.21
==============================
* updated 'use it in your project' section in demo

v0.2.20
==============================
* Install new version of `px-sass-doc` component
* Fix import comment in code
* Remove `--strip-comments` flag from vulcanize

v0.2.19
==============================
* updated demo

v0.2.18
==============================
* fixed demo for Travis

v0.2.17
==============================
* added new demo and auto-ghp
* added missing dark-grey to behavior

v0.2.16
==============================
* updated README

v0.2.15
==============================
* added @polymerBehavior to the behavior for proper polymer docs behavior

v0.2.14
==============================
* Created variable set "grey" which is equal to "gray" to avoid developer typos.

v0.2.13
==============================
* Fixed a variable type in the py file which lead to an incorrect var name in the html

v0.2.12
==============================
* Created a python converter to consume the SCSS and generate a HTML with the colors as Polymer Properties.
* HTML file can be used as a Polymer behavior for our components.

v0.2.11
==============================
* Added OSS notice and changed the repo to be public in bower.

v0.2.10
=====================
* Updated License

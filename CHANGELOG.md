## 1.0.8

* added rightToLeft parameter to README

## 1.0.7

* made it possible to make a dark mode without changing the theme with an example
* added an example for ellipsis text overflow handling
* made it possible to support right to left languages with an example

## 1.0.6

* selectable items can be added and removed by the user

## 1.0.5

* added demonstration for disabled and readOnly
* test formatted
* added readOnly and menuBackgroundColor parameters
* clear icon disabled when Widget is disabled

## 1.0.4

* minor changes to CI/CD
* git cleanups

## 1.0.3

* minor improvements to README

## 1.0.2

* minor improvements to README

## 1.0.1

* CI/CD improved automated deployment

## 0.0.1

Improvements on a pull request that was probably changing too many things to be accepted of the great icemanbsi's searchable_dropdown:
https://github.com/icemanbsi/searchable_dropdown/pull/11
Part of the pull request I proposed:
* keyboardType
* validator
* label
* searchFn
* multipleSelection

New with this repository:
* demo app with a gallery as tabs or as a single page (change through a switch)
* automated testing
* continuous integration (CI)
* continuous deployment (CD)
* license is MIT
* split constructors between single and multiple selection
* comments on the constructors
* selection can be done in a menu, not just a dialog box
* solution to allow flexibility to provide a String, a Widget or a Function that returns either one of String or Widget for several components of the Widget
* documentation
* keyboard doesn't overlap dialog

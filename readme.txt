=== pdf2wp ===

Contributors: formula1, here
Donate link: http://in-space.org
Tags: pdf
Requires at least: 0.1
Tested up to: 0.1
Stable tag: 0.2
License: GPLv3 or later
License URI: http://www.gnu.org/licenses/gpl

== Description ==

pdf2wp WordPress plugin

Created as a git exercise at [git Together in space](http://website.in-space.org/git-together/) ~2

WordPress plugin converts an uploaded pdf to a WordPress post using the pdftotext utility.

== Changelog ==

= 2015-06-13 v0.2 =
* readme
* GPLv3
* init docs

= 0.1 =
* init

== Dependencies ==

* pdftotext -- https://en.wikipedia.org/wiki/Pdftotext

== Pseudo Code ==

Creating an admin page to upload pdf
* On upload, convert pdf to text
** exec(pdftotext)
** alternative ideas
*** remote API convert
*** ImageMagick
*** PDF Grep

Allow Raw PDF Viewing
* viewer PDF.js https://github.com/mozilla/pdf.js/

Custom Post Type?
* Maybe...

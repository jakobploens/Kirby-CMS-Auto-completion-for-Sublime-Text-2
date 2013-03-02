# Kirby CMS Auto-completion for Sublime Text 2
This package provides you with the whole Kirby-API as shortcuts for Sublime Text 2. Follow the installation instructions down here to get your hands on that. All methods are out of the Kirby Cheat Sheet.

The package contains **only** the commands from the Kirby Cheat Sheet, so there's no `kirbytext()`, `html()` and things like that (maybe it'll be there sometime – see more on that on "upcoming").

## Current Version
Contains all commands of Kirby v1.1.

## Issues
There is only one issue, but this is such a problem that it destroys the whole awesomeness of such a file. I don't know how to fix it – if you know it, it would be great if you could do a pull request or drop me a line [@plartz](http://twitter.com/plartz) or by [mail](mailto:post@jakobploens.de).
The things is that Sublime Text 2 seems to stop autocompletion if you enter the `>` symbol. Quite a big problem, because the Kirby API is jQuery-inspired, and is like `$page->title()`. So you can just enter the first part (e.g. `$page`) and then either type your command manually (because it won't show you the command's list if you type `->`) or select your command out of this heavy list. Just try it out. It's mad, I know, but like I said, I don't know how to fix that. But maybe the package comes in handy for you anyway.

## Installation
Just download all files and place them into a new folder "kirby" in your Packages folder.
- OS X: *~/Library/Application Support/Sublime Text 2/Packages*
- Windows: *%APPDATA%\Sublime Text 2\Packages*
- Linux: *~/.config/sublime-text-2/Packages*
(for more information on the data directory of Sublime Text, have a look at the [Documentation](http://docs.sublimetext.info/en/latest/basic_concepts.html#the-data-directory))

## Upcoming
I don't promise anything, because I'm really really busy at the moment, but maybe I (or somebody else) will add some snippets (like a breadcrumb, a short menu, some short tags…). And of course things like `kirbytext()`, `html` and those helpers are missing – I think this will be the first thing to add. So, just open Sublime Text and add some files to this repo…

## Note
© 2013 by [Jakob Plöns](http://jakobploens.de) (post@jakobploens.de).
Kirby © 2009-2013 [Bastian Allgeier](http://bastianallgeier.com/) / [OpenWe GmbH](http://openwe.de/).
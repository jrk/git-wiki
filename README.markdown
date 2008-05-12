# git-wiki #

A wiki engine that uses a Git repository as its data store.

## Status ##

Alex Payne (see AUTHORS file) is no longer actively developing this branch.
Please fork from here and continue development!

## Requirements ##

* rubygems
* sinatra
* grit
* redcloth
* bluecloth
* rubypants
* git
* metaid


Sinatra is vendored as a [git submodule][gs].
To get it, run the fellowing commands :

    % cd git-wiki
    % git submodule init
    % git submodule update

## Usage ##

The app stores the wiki contents as a Git repository in `${HOME}/wiki/`.


[gs]: http://www.kernel.org/pub/software/scm/git/docs/git-submodule.html

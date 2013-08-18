# My jekyll layouts

To support similar looking github pages across all my repos (if I so choose) I
submodule this as the `_layouts` folder.

## Use

    $ git submodule add git@github.com:natronics/jekyll-layouts.git _layouts
    $ git commit -m "adding jekyll layout submodule"
    $ git submodule init

## Update

    $ cd _layouts
    $ git checkout master
    $ git pull
    $ git commit -am "Pulled down update to submodule_dir"

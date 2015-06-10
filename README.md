# go bash completion

*this is a work in progress, still considering other ways to implement things*

Initially this bash completion is based on [the one removed from the go repository](https://codereview.appspot.com/105470043/patch/40001/50002).

# Added features

## Cache of go package list

Output of "go list all std" is stored inside an an environment variable, so it's on a per shell level.
The `_go_clear_cache` function clears the cache if needed. 

## What are the alternatives?
* [deleted from go/misc/bash/go](https://codereview.appspot.com/105470043/patch/40001/50002)
* [github.com/kura/go-bash-completion](https://github.com/kura/go-bash-completion/blob/master/etc/bash_completion.d/go)
* [gihub.com/skelterjohn/go-pkg-complete/](https://github.com/skelterjohn/go-pkg-complete/blob/master/go-pkg-complete.bash.inc)
* [github.com/omakoto/go-completion.bash](https://github.com/omakoto/go-completion.bash/blob/master/go-completion.bash)


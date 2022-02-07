# void-vscode-ripgrep

The original package, @vscode/ripgrep, adds a lot of complexity in order to install a fitting version of ripgrep. However, this clashes with void linux's xbps-src installation and is not really necessary, since we already have the newest correct version installed.

So this only points vscode in the direction of the rg binary and be done with it, saving a lot of time and hassle.

A previous version to replace @vscode/ripgrep featured the original code, but has the disadvantage of adding extra complexity for maintenance when all that is actually used is the file path to said binary.

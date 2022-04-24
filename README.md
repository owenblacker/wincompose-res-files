# Resource files for WinCompose

Upgrading Sam Hocevar's awesome [WinCompose](http://wincompose.info/) [`samhocevar/wincompose`](https://github.com/samhocevar/wincompose) used to overwrite my resource files, where I have a shitload of custom key combinations installed, because I wasn't using the `~/.XCompose` file to hold them.

After comparing against a manually archived version of my files a few upgrades ago, I figured I should just create a repo so I can get a changelog as well as easy diffing. Then, when I moved to a new laptop, I figured I should turn them into files for inclusion into my `~/.XCompose` file instead, using the format `include /path/to/file.XCompose`.

The `sh` script `copy-to-home.sh` will copy all files matching `*.XCompose` to the current user's home directory.

[@owenblacker](https://twitter.com/owenblacker), 24 April 2022

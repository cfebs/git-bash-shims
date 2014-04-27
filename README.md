# git-bash-shims

Have recently been obsesed with having a decent shell in windows which means using [msysgit](http://msysgit.github.io/)

Lots of bash commands are supported, but some are not.

## Usage

- Clone repo somewhere
- Add this repo's `bin` directory at the **beginning** of your path in your `$HOME/.bashrc`

    export PATH="$HOME/src/git-bash-shims/bin:$PATH"

## Commands Shimmed

### ln

Only soft links `-s` are supported.

`-f` also supported

Uses windows internal [mklink](http://en.wikipedia.org/wiki/NTFS_symbolic_link)

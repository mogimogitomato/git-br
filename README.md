# git-br

git branch wrapper command

## Usage

```zsh
$ git br [-f][-d][-s]

OPTIONS:
  -f       when switching remote branch and local branch already exists,
           delete local branch before switching.
  -d       delete previous current branch after switching.
  -s       sync remote and delete branches that merged into current branch. (no switching.)
```

## Installation

```zsh
zplug "jhawthorn/fzy", \
    as:command, \
    hook-build:'make'
zplug "b4b4r07/git-br", \
    as:command, \
    use:'git-br'
```

## License

This repository is forked from `b4b4r07/git-br` (MIT @ b4b4r07).

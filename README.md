git-git
-------

`git-git` is a tiny git extension that autocorrects when you type `git` twice:

```
$ git git status
git: 'git' is not a git command. See 'git --help'.

Did you mean this?
	init
```

Read more about why this exists and how it works in the [blog post about
git-git][post].

  [post]: https://bernerdschaefer.com/2016/11/17/git-git-the-world-s-smallest-git-plugin.html

## Install

Copy `git-git` onto your shell's path, add it to your dotfiles, or install
with Homebrew:

```
$ brew install bernerdschaefer/formulae/git-git
```

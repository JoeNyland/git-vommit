# git-vommit

How many times have you gone to `git commit` and typed `git vommit` instead? :rage:

As the title suggests, this plugin makes Git vomit, so you learn the hard way *not* to type `git vommit`. :stuck_out_tongue_winking_eye:

## WARNING
This is a silly little plugin and should obviously not be installed anyway near a production server. You've been warned!

## Installation

### MacOS via Homebrew
`brew install joenyland/git/git-vommit`

Or `brew tap joenyland/git` and then `brew install git-vommit`.

### Gentoo

```
layman -o https://raw.githubusercontent.com/JoeNyland/gentoo-overlay/master/repositories.xml -f -a joenyland
emerge dev-vcs/git-vommit
```

### Source
Clone the repo:
```
git clone https://github.com/JoeNyland/git-vommit.git
```
`cd` into the repo:
```
cd git-vommit
```
Run the installation routine (requires `make`)
```
make install
```

## Usage
Just [accidentally] type `git vommit` from a Git repo
![Demo](demo.gif)

## Uninstall
`cd` into the repo:
```
cd git-vommit
```
Run the uninstall routine (requires `make`)
```
make uninstall
```

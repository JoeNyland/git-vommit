# git-vommit

How many times have you gone to `git commit` and typed `git vommit` instead? :rage:

As the title suggests, this plugin makes Git vomit, so you learn the hard way *not* to type `git vommit`. :stuck_out_tongue_winking_eye:

## WARNING
This is a silly little plugin and should obviously not be installed anyway near a production server. You've been warned!

## Installation

### Homebrew
`brew install masterroot24/git/git-vommit`

Or `brew tap masterroot24/git` and then `brew install git-vommit`.

### Source
Clone the repo:
```
git clone https://github.com/MasterRoot24/git-vommit.git
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

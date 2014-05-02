# DosAmp's dotfiles

## About

This repository represents my personal spin of
[dotfiles](https://dotfiles.github.io/). These files are a common denominator
shared among unixoid installations on my computers.

## SSH public keys

In May 2014, I converted my SSH infrastructure to use one private key per
client, not per server. **ssh/publickey_bundle** contains a list of all new
public keys issued in the process.

Don't worry! If you want to grant me access to your server which only
supports public key authentification, you don't have to copy the whole bundle
to `~/.ssh/authorized_keys`, although I recommend that procedure for the sake
of consistency and simplicity. Otherwise, I'll ask for access using my
current computer's public key and add the rest later.

A list of computer descriptions and key fingerprints can be found in
**ssh/fingerprints.csv**.

## TODO

* code bootstrap framework (or better, re-use from other dotfiles
  repositories) for easy deployment

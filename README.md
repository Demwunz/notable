# Use [Keybase](https://keybase.io) to hold encrypted notes for [notable app](https://notable.md)

My notes for notable app v1.8.0

Assumes you've set up a private git repo inside keybase to hold your encrypted notes.

Setting up on a new machine:

```sh
$ brew cask install notable keybase
```

```sh
$ git submodule update --init --recursive
```

In case of `fatal: transport 'keybase' not allowed`

```sh
$ git config --global --add protocol.keybase.allow always
```

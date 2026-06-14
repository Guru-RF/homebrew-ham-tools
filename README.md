# homebrew-ham-tools

A [Homebrew](https://brew.sh) tap for [ham-tools](https://github.com/Guru-RF/ham-tools) —
command-line amateur-radio tools (`qrz`, `qte`, `dxsummit`, `dxheat`, `holycluster`).

## Install

```sh
brew tap Guru-RF/ham-tools
brew install ham-tools
```

Homebrew may ask you to trust this third-party tap the first time you use it:

```sh
brew trust guru-rf/ham-tools
```

Or, to build the latest development version straight from `master`:

```sh
brew install --HEAD Guru-RF/ham-tools/ham-tools
```

The formula lives in [`Formula/ham-tools.rb`](Formula/ham-tools.rb). It is a copy
of the formula tracked in the main [ham-tools](https://github.com/Guru-RF/ham-tools)
repo — update it there and copy it across when cutting a release.

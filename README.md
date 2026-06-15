# homebrew-ham-tools

A [Homebrew](https://brew.sh) tap for [ham-tools](https://github.com/Guru-RF/ham-tools) —
command-line amateur-radio tools (`qrz`, `qte`, `dxsummit`, `dxheat`, `holycluster`).

## Install

```sh
brew tap Guru-RF/ham-tools
brew install ham-tools
```

If Homebrew refuses to load the formula from this untrusted third-party tap,
trust it once and re-run the install:

```sh
brew trust Guru-RF/ham-tools
```

Or, to build the latest development version straight from `master`:

```sh
brew install --HEAD Guru-RF/ham-tools/ham-tools
```

The formula lives in [`Formula/ham-tools.rb`](Formula/ham-tools.rb). It is a copy
of the formula tracked in the main [ham-tools](https://github.com/Guru-RF/ham-tools)
repo — update it there and copy it across when cutting a release.

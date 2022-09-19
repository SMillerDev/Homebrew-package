# Usage

- Generate the package:
```sh
pkgbuild --root brew --install-location "/tmp/brew/" --identifier sh.brew.Homebrew --scripts scripts --min-os-version 11.0 --filter .DS_Store --version 1 Homebrew.pkg
```
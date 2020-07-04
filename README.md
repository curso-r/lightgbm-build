
# LightGBM builds

<!-- badges: start -->
<!-- badges: end -->

This repository provides binary builds of the `lightgbm` R package to make
installation easier. See installation instrucctions below for each platform.

# MacOS

You need to install gcc and libomp:

```
brew install gcc
brew install libomp
```

Then you can run:

```
install.packages(
  sprintf(
    "https://github.com/curso-r/lightgbm-build/releases/download/macos-r-%d.%d/lightgbm_2.3.2.zip",
    getRversion()$major, getRversion()$minor
  ),
  repos = NULL
)
```

## Windows

On windows just run:

```
install.packages(
  sprintf(
    "https://github.com/curso-r/lightgbm-build/releases/download/windows-r-%d.%d/lightgbm_2.3.2.zip",
    getRversion()$major, getRversion()$minor
  ),
  repos = NULL, type = "win.binary"
)
```

## Ubuntu 18.04

```
install.packages(
  sprintf(
    "https://github.com/curso-r/lightgbm-build/releases/download/ubuntu-18.04-r-%d.%d/lightgbm_2.3.2_R_x86_64-pc-linux-gnu.tar.gz",
    getRversion()$major, getRversion()$minor
  ),
  repos = NULL
)
```

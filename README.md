
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
install.packages("https://github.com/curso-r/lightgbm-build/releases/download/macos/lightgbm_2.3.2.tgz")
```

## Windows

On windows just run:

```
install.packages("https://github.com/curso-r/lightgbm-build/releases/download/windows/lightgbm_2.3.2.zip", 
                 repos = NULL, type = "win.binary")
```



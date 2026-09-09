# homebrew-wine

This tap provides the following casks:

* `wine-stable`
* `wine@devel`
* `wine@staging`
* `gstreamer-runtime`

Taken from the official Homebrew casks, with the disable calls removed.

## Installation

Tap the repository:

```
brew tap corncobble/wine
```

Trust the repository:

```
brew trust corncobble/wine
```

Then install the desired wine cask (along with the `gstreamer-runtime` dependency):

```
brew install corncobble/wine/gstreamer-runtime corncobble/wine/wine-stable
```

## Upstream

The Wine binaries are built and distributed by Gcenx:

https://github.com/Gcenx/macOS_Wine_builds

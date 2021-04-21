# ggb-manipulator

This low-level toolset allows manipulating GeoGebra's .ggb files with support for batch processing.

For example, one wants to change the title in a set of .ggb files, but manual edit is slow and not elegant.
Instead, a script can do the following:

1. Unzip the .ggb file in a temporary folder.
2. Change the file geogebra.xml by using a batch XML editor, for example, `xmlstarlet`.
3. Zip the folder again as the same (or another) .ggb file.

If you need to do this on a frequent basis, **ggb-manipulator** is your friend.

## Prerequisites

**ggb-manipulator** runs in a Unix environment and tested on Ubuntu Linux 20.04.

You need the following packages to make it work:

* bash
* coreutils
* zip
* xmlstarlet

## Usage

See the folder [examples](examples/).

## Author

Zoltán Kovács <zoltan@geogebra.org>

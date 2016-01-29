# Welcome to pyBarcode #

This module was created, because all barcode modules I found on the net required PIL to work.
The idea was to create a module, which can create barcodes out of Python's standardlib and is easy extensible to add new writer.
Note that this software is under development and the API can change on every release. The basic usage (Barcode.render and Barcode.save)
will not change, but the internals.

## Requirements ##

  * Python >= 2.6 (but < 3.0)
  * SVG viewer

## Installation ##

Download the latest release, cd into the unpacked directory and run ` python setup.py install ` or just copy the barcode directory somewhere in your PYTHONPATH.
This package is also listed in PyPI, you can run
` easy_install pyBarcode ` to install it.
If you want the latest development version, install [Mercurial](http://mercurial.selenic.com/wiki/)  and run:
```
hg clone https://code.google.com/p/python-barcode/
```


## License ##

This software is licensed under the [MIT license](LicensePage.md).

## Links ##

You can browse the documentation online [here](http://packages.python.org/pyBarcode/).
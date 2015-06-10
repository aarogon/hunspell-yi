Hunspell Yiddish dictionary
===========================

This is a Yiddish dictionary for [Hunspell](http://hunspell.sourceforge.net/).

Installation
------------

* Clone the repository (or download the files as [zip](https://github.com/har-wradim/hunspell-yi/archive/master.zip)):

        git clone https://github.com/har-wradim/hunspell-yi.git

* Copy the yi.dic and yi.aff files to a place accessible by hunspell. Under Linux the following paths should work out of the box:

        sudo cp yi.aff yi.dic /usr/share/hunspell/
        sudo ln -sf /usr/share/hunspell/yi.dic /usr/share/myspell/dicts/yi.dic
        sudo ln -sf /usr/share/hunspell/yi.aff /usr/share/myspell/dicts/yi.aff

Credits
-------

The dictionary is based on the corpuses collected by [Raphael A. Finkel](http://www.cs.uky.edu/~raphael/yiddish.html), [Simche Taub](http://jidysz.net/) and [Andrey Rozenberg](https://github.com/har-wradim). The spelling is unified in line with the rules codified in [כלל־תקנות פון יידישן אויסלייג](http://dovidkatz.net/dovid/PDFStylistics/1992.pdf)

License
-------

Inherits the GPL v.3 License.

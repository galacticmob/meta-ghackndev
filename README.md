# meta-ghackndev

This layer is for maintenance of support for old (and some not so old) 
handheld devices, including Sharp Zaurus, HP iPAQ etc, initially based upon
recipes from OpenEmbedded master. Note that some machines may have suffered
from bitrot and need work, your help would be appreciated!


Dependencies
------------

This layer depends on:

layer: OE-Core
URI: git://git.openembedded.org/openembedded-core
branch: master
revision: HEAD

layer: meta-initramfs
URI: git://git.openembedded.org/meta-openembedded
branch: master
revision: HEAD


Maintenance
-----------

Send patches / pull requests to this repository
with '[meta-ghackndev]' in the subject.

Main layer maintainer: Connor O'Brien <connor607@gmail.com>


License
-------

All metadata is MIT licensed unless otherwise stated. Source code included
in tree for individual recipes is under the LICENSE stated in each recipe
(.bb file) unless otherwise stated.

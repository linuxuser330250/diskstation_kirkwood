Repository for Synology DiskStation DS409slim
=============================================

* Maintainer: Linux User #330250
* Purpose: provide files for the DS409slim and compatibles
* Current supported DSM release: 4.2

Resources
---------

You should read other resources in order to make safe use of this repository.

* [SynologyWiki](http://forum.synology.com/wiki/index.php/Home)
* [Overview on modifying the Synology Server, bootstrap, ipkg etc](http://forum.synology.com/wiki/index.php/Overview_on_modifying_the_Synology_Server,_bootstrap,_ipkg_etc)

Compatibility
-------------

Packages provided here should work for all **ARMv5TE** compatible CPUs, even
thou they are specifically and have been tested on the **Marvell Feroceon**
**[88F6281](http://www.marvell.com/embedded-processors/kirkwood/assets/88F6281-004_ver1.pdf)**
SoC, part of the **Marvell**
**[Kirkwood series](http://www.marvell.com/embedded-processors/kirkwood/)** of
processors. This is the SoC used in the Synology DiskStation DS409slim. Check if
your DiskStation uses a compatible ARMv5TE processor and you should be safe.

* [What kind of CPU does my NAS have](http://forum.synology.com/wiki/index.php/What_kind_of_CPU_does_my_NAS_have)?

Packages
--------

* **idle3-tools**

  A tool to set the idle3 flag on Western Digital Green hard disk drives.
  Normally you would need to connect a WD Green drive to a PC and run the
  original [WDIDLE3.EXE program](https://www.synology.com/en-uk/knowledgebase/faq/407)
  to set the idle timer, but with this Linux tool you can set in on the command
  line interface (CLI) directly after installing it via ipkg on the DiskStation.

Scripts
-------

* *none for now*

Licenses
--------

All provided software is provided in ready-to-use form, but the license files
have been excluded to keep the installation packages as slim as possible.

The licenses are included as files in the *licenses* folder of this repository.

Displaimer
----------

This repository is intended for my personal use, but since it may also be useful
for others it is provided publicly AS-IS, without any warranty of any kind.
**You use this repository AT YOUR OWN RISK.**

Please also read the
[General Disclaimer on Modifying the Synology Server](http://forum.synology.com/wiki/index.php/General_Disclaimer_on_Modifying_the_Synology_Server)
from the SynologyWiki community resource guide.

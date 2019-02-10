Metadata Tab (plugin for Mirador)
=================================

[Metadata Tab] is a plugin for [Mirador], an [IIIF] advanced viewer, that
displays the metadata of the currently shown image (canvas) in the left panel.

This plugin is automatically included in the module [Mirador Viewer] for [Omeka S].


Installation
------------

Enable the plugin by including the CSS and the JavaScript (**after** loading Mirador):

```html
<link rel="stylesheet" type="text/css" href="<url to the plugin>/metadataTab.css" />
...
<script src="<url to the plugin>/metadataTab.js"></script>
```


Usage
-----

The metadata are automatically displayed in the left sidebar when any.


Warning
-------

Use it at your own risk.

It’s always recommended to backup your files and your databases and to check
your archives regularly so you can roll back if needed.


Troubleshooting
---------------

See online issues on the [plugin issues] page on GitHub.


License
-------

This module is published under the MIT licence.

This plugin is based on the core code of Mirador and on [CanvasLink] of the
Digital Library/Munich Digitization Centre at the Bavarian State Library.


Copyright
---------

Widget [Mirador]:

* Copyright 2018 The Board of Trustees of the Leland Stanford Junior University

Plugin MetadataTab:

* Copyright Daniel Berthereau, 2019

First version of this plugin was built for [Fachhochschule Nordwestschweiz],
University of Applied Sciences and Arts, Basel Academy of Music, Academy of Music,
[Schola Cantorum Basiliensis].


[Metadata Tab]: https://github.com/Daniel-KM/Mirador-plugin-MetadataTab
[Mirador]: https://projectmirador.org
[IIIF]: http://iiif.io
[Mirador Viewer]: https://github.com/Daniel-KM/Omeka-S-module-Mirador
[Omeka S]: https://omeka.org/s
[CanvasLink]: https://github.com/dbmdz/mirador-plugins/blob/master/CanvasLink
[plugin issues]: https://github.com/Daniel-KM/Mirador-plugin-MetadataTab/issues
[Fachhochschule Nordwestschweiz]: https://www.fhnw.ch
[Schola Cantorum Basiliensis]: https://www.fhnw.ch/en/about-fhnw/schools/music/schola-cantorum-basiliensis
[Daniel-KM]: https://github.com/Daniel-KM "Daniel Berthereau"

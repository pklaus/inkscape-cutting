inkscape-cutting
================

An extension to export cutting positions from Inkscape for use
with cutting plotters. 100% pure Python.

Installation
------------

    cd ~/.config/inkscape/extensions/
    # or on Mac OS X:
    cd /Applications/Inkscape.app/Contents/Resources/extensions/
    git clone https://github.com/pklaus/inkscape-cutting.git
    ln -s ./inkscape-cutting/cutting.inx cutting.inx

Restart inkscape

Origin
------

This plugin originated as [inkscape-silhouette][].
The reason I transformed it to this extension is that I found it
cumbersome to work with hardware directly from within an Inkscape
extension. By separating the **Inkscape SVG -> cut position**
functionality from the **cut position -> hardware instructions**
and **hardware instructions -> send to hardware device** functionaly
I gained a lot of freedom in which device to plot with and which
programming language to use for it.

[inkscape-silhouette]: https://github.com/fablabnbg/inkscape-silhouette

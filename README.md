# kalonline-mod-collection
[![Build Status](https://travis-ci.org/madnight/kalonline-mod-collection.svg?branch=master)](https://travis-ci.org/madnight/kalonline-mod-collection)
[![License: GPL v2](https://img.shields.io/badge/License-GPL%20v2-blue.svg)](https://www.gnu.org/licenses/gpl-2.0.html)

This repo contains old code written for the game [Kal Online](https://en.wikipedia.org/wiki/Kal_Online). This is basically a collection of some (cool) game modifications like extra commands, server and clientside cheat protection, level extension, monster spawns, ... . Since Kal Online is a closed source game the only way to modify the game is via low level hooks, hence i used C++ and inline assembly. There is a more or less inactive development forum section on [Ragezone](http://forum.ragezone.com/f241/) were we shared our thoughts, code and ideas. Since i left the dev community some years ago and my code is also published there, i simply thought why not adding it here. The code is very ugly written (cryptic inline assembly, no code conventions, crap ...), you have been warned.

Tools i used:

 - [IDA Pro](https://www.hex-rays.com/products/ida/)
 - [OllyDbg](http://ollydbg.de/)
 - Visual Studio 2010

<pre><code>-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
C++                             66           1762           1693           9501
C/C++ Header                    84           1273           2013           8686
YAML                             2              3              0             21
Bourne Shell                     1              1              0              8
-------------------------------------------------------------------------------
SUM:                           153           3039           3706          18216
-------------------------------------------------------------------------------
</code></pre>

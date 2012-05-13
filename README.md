impactjs-pHash
==============

Concise Perl style hash implementation for the ImpactJS engine.

Hash Table implementation to have Perl style hash behavior in JavaScript and ImpactJS

Implementation inspired by Mojavelinux, Inc.
http://www.mojavelinux.com/articles/javascript_hashes.html

As the author of the article above notes, there are many libraries out there that are bery well tested and more robustly implemented, like say jQuery.js! Also noted is that a JavaScript object is basically a hashTable with most of these properties already built in. 

All that said, the goal of this plugin is to provide a clean and concise Perl style Hash implementation for the ImpactJS architecture.

Simply include the plugin and create a '''javascript new pHash '''
The available operations are:
* set(key, value)
* get(key)
* has(key)
* pop(key)
* keys()
* values()
* each(fxn)
* clear()

This is currrently used in PiSpace: http://www.clokwork.net/pispace

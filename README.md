famfamfam-flags
===============


[![NPM version](https://img.shields.io/npm/v/famfamfam-flags.svg)](https://www.npmjs.org/package/famfamfam-flags)
[![Bower version](https://img.shields.io/bower/v/famfamfam-flags.svg)](http://bower.io/search/?q=famfamfam-flags)
[![Packagist version](https://img.shields.io/packagist/v/t1st3/famfamfam-flags.svg)](https://packagist.org/packages/t1st3/famfamfam-flags)



About
----------

The `Flags` icon pack, as available on [famfamfam website](http://www.famfamfam.com/lab/icons/flags/).

All credits for these icons go to their original author: Mark James (mjames@gmail.com)

The aim of this project is to make this icon pack available through various package managers, such as:

- [NPM](https://npmjs.org)
- [Bower](http://bower.io)
- [Packagist](https://packagist.org)


All icons are supplied in both PNG and GIF formats.




Extension
----------

Note that 1 flag has been added to the original package: `gg.png` (or `gg.gif`).

This flag was created by Damien Guard (damieng@gmail.com), in the "add-on" package for FamFamFam icons named [Silk Companion](http://www.damieng.com/icons/silkcompanion).




CSS spritesheets
----------

You can insert the icons directly into your HTML with a common IMG tag:

```
    <img alt="French Flag" src="dist/png/fr.png" width="16" height="11">
```


In addition to the icons by themselves, this project also ships a CSS spritesheet for the icon-pack. This spritesheet allows to load the entire icon-pack in just 1 image, and thus reduce HTTP calls.

All the positioning of the icons inside this alone image is made through CSS, which allows you to just add block-type tags with the proper class and get the same result:

```
    <div class="famfamfam-flags fr"></div>
```

Just remember to add the CSS stylesheet to the HEAD of your HTML page!



Original readme (from author of the icons)
----------

Flag icons - [http://www.famfamfam.com](http://www.famfamfam.com)

These icons are public domain, and as such are free for any use (attribution appreciated but not required).

Note that these flags are named using the ISO3166-1 alpha-2 country codes where appropriate. 
A list of codes can be found at [http://en.wikipedia.org/wiki/ISO_3166-1_alpha-2](http://en.wikipedia.org/wiki/ISO_3166-1_alpha-2)

If you find these icons useful, please donate via paypal to mjames@gmail.com 
(or click the donate button available at [http://www.famfamfam.com/lab/icons/silk](http://www.famfamfam.com/lab/icons/silk))

Contact: mjames@gmail.com



Original readme (from the author of the extension "Silk Companion")
----------

Silk companion icon set #1 - "More Silk!"
Last updated: 19 November 2007

_________________________________________
Damien Guard
http://www.damieng.com/icons/silkcompanion
_________________________________________

This work is licensed under a
Creative Commons Attribution 2.5 License.
[ http://creativecommons.org/licenses/by/2.5/ ]

The FamFamFam Silk icon set is a very large,
consistent set of well-drawn icons that has
proven to be popular with both applications
and web sites.

On a number of occasions I have found myself
wanting more icons in the same style. This 
companion set represents what I needed but also
what I felt like adding.

Some are new icons in the same style, some are
alternative sizes/colours of the existing icons
and some are new compositions of the elements.

Any questions about this companion set please
contact damieng@gmail.com.






About the rest (all this repository but the icons)
----------

All the content of this repository (excepted the icon pack) 
is licensed under the [MIT license](http://opensource.org/licenses/MIT).

Though, it is just composed a few trivial json files and a Readme.


Get the package
----------

**NPM**

Get it with:

```
npm install famfamfam-flags
```


**Bower**

Get it with:

```
bower install famfamfam-flags
```

**Composer / Packagist**

[famfamfam-flags on Packagist](https://packagist.org/packages/t1st3/famfamfam-flags)





Dev dependencies and build status
----------

[![Dependency Status](https://img.shields.io/david/dev/T1st3/famfamfam-flags.svg)](https://david-dm.org/t1st3/famfamfam-flags)
[![Build Status](https://img.shields.io/travis/T1st3/famfamfam-flags.svg)](https://travis-ci.org/T1st3/famfamfam-flags)




---
layout: default
title:  "Sublime Text 3"
date:   2013-06-05 20:03:11
tags: about
---
## Sublime Text 3
The first package you need to install is called <a href="https://packagecontrol.io/" target="_blank">Package Control</a>. The <a href="https://packagecontrol.io/installation">installation is </a> varied between Sublime Text 2 and Sublimte 3.

As for ST3, it can be installed by pressing *cltr+`* or go thourgh view>Show Console and paste the folllowing python code and press enter.

    import urllib.request,os,hashlib; h = '2915d1851351e5ee549c20394736b442' + '8bc59f460fa1548d1514676163dafc88'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)

After installing Package Control manager, the pacakges can be installed through the channels by pressing *cltr+shift+p*, and type *install* and press enter. Click the below links to find the best pacakge you can get for ST3. 

The full directory of Sublime Text packages can be found at <a href="https://packagecontrol.io/browse">package control Browse</a>.

## [Language Specific](../../st3/language)

## [Code Completion](../../st3/completion)

## [Code Display](../../st3/code_display)

## [Integrations](../../st3/integrations)

## [Intefaces](../../st3/interface)

## [Commands](../../st3/commands)

## [Others](../../st3/other)

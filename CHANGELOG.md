# WebDNA Language Extension for VSCode Changelog

## (06/02/2021) v-0.0.5:
    - Updated parameter highlighting to be case insensitive
    - Fixed parameter scope issues
    - Added/updated support for the highlighting of:
        * Support tags: validcard, findstring, filecompare
        * Support parameters for tags: validcard, findstring, filecompare

## (06/02/2021) v-0.0.4:
    - Added basic support for html, css, sql, xml, javascript, and json

## (05/29/2021) v-0.0.3:
    - Added/updated support for the highlighting of:
        * Keyword tags: switch, case, hideif, showif, if, then, else, default
        * Keyword parameters for tags: switch, case, redirect
        * Depreciated keyword tags: html1, html2, html3
        * Storage tags: text, math, function
        * Storage parameters for tags: text, math, function
        * Support tags: authenticate, calcfilecrc32, clearlineitems, closedatabase, commitdatabase, copyfile, copyfolder, createfolder, date, deletefile, deletefolder, getcookie, getmimeheader, movefile, protect, purchase, random, renamefile, removelineitem, setcookie, setmimeheader, time
        * Support parameters for tags: authenticate, calcfilecrc32, clearlineitems, closedatabase, commitdatabase, copyfile, copyfolder, createfolder, date, deletefile, deletefolder, getcookie, getmimeheader, movefile, protect, purchase, random, renamefile, removelineitem, setcookie, setmimeheader, time

## (05/28/2021) v-0.0.2:
    - Updated patterns to recursivly apply patterns to correctly stylize tags inside tags
    - Updated various scope selectors
    - Added support for the highlighting of:
        * global tags: username, authenticate, calcfilecrc32, clearlineitems, closedatabase, commitdatabase, copyfile, copyfolder, createfolder, date, delete, deletefile, deletefolder, filecompare, getcookie, getmimeheader, include, lookup, movefile, password, protect, purchase, random, removelineitem, renamefile, setcookie, setmimeheader, time, validcard, findstring
        * keyword tags: if, else, then, redirect, hideif, showif
        * contexts: applescript, capitalize, countchars, ddesend, dos, html1, html2, html3, input, interpret, listdatabases, lineitems, raw, shell, spawn, unurl

## (05/27/2021) v-0.0.1:
    - Added support for block comments ([!][/!]) in the language configuration
    - Added support for the highlighting of:
        * text and math tags
        * contextual tags: founditems, return, url
        * webdna variables
        * block comments
        * double and single quoted strings
        * global tags: browsername, cart, command, elapsedtime, flushdatabases, flushcache, freememory, httpmethod, ipaddress, issecureclient, lastautonumber, lastrandom, platform, product, random, referrer, referer, thisfile, thisurl, thisurlplusget, version

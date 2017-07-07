# miscXQuery
Miscellaneous XQuery code

This repository is a collection of stand alone XQuery library modules.


## encchars.xqy

The module contains variables for each of the unicode escape sequences at 
[https://en.wikipedia.org/wiki/List_of_XML_and_HTML_character_entity_references](https://en.wikipedia.org/wiki/List_of_XML_and_HTML_character_entity_references)

Here is an example for using the library.

```
xquery version "1.0";

import module namespace encchars="http://w3.org/encoded/characters" at "/encchars.xqy";

<foo>{$encchars:dagger}{$encchars:Dagger}</foo>

```

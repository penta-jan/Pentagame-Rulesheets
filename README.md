##  Pentagame Rulesheets.

If you want to contribute a language, please just copy one of the language files (e.g. english.tex) and translate, leaving line breaks and commands intact.

The way this works is that the main TeX file calles such a package and then the layout file, then the next langauge and the layout file again, and so forth, to produce all the languages in the same layout. So once you're done with your new language file, you can also add it into the main file.

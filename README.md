XML exports uit MAIS (ook wel "MAIS XML") bevatten vrijwel nooit syntactisch correcte XML.

Dit script voert een paar simpele _search and replaces_ uit om deze syntax-errors op te lossen.

# Dependencies

* `sd`
* `fish`

# Instructies

``` fish
$ fixmaisxml --help
Transform MAIS XML into well-formed XML

Usage: fixmaisxml FILE.xml [FILE2.xml ...]

$ fixmaisxml *.xml # fix alle MAIS XML in de huidige map
```

# Installatie

1. `git clone` deze repo
2. Kopieer of symlink `fixmaisxml` ergens in je `PATH`, bijvoorbeeld in `/usr/local/bin/`

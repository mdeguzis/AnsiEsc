ANSI Highlighting
=================

This is github page of this plugin
http://www.drchip.org/astronaut/vim/index.html#ANSIESC
by Charles E. Campbell

Updated Feb 18, 2017 (v13l)

This plugin follows ANSI-escape sequences to colorize subsequent text using
vim's syntax highlighting engine.

The AnsiEsc plugin provides a single command: `:AnsiEsc`, which will toggle
ANSI-escape sequence processing. When enabled, AnsiEsc will handle `<esc>[FGm%`,
`<esc>[ATTR;FGm`, and `<esc>[FG;BGm` sequences; subsequent text will then be
colored appropriately.

With vim 7.2 and earlier, the escape sequence itself will take space but will be
suppressed using "Ignore" highlighting. Vim 7.3 comes with Vince Negri's
conceal/ownsyntax capabilities built-in. With it, ANSI-escape sequences will
have their colorizing effects but will themselves be concealed (again, when
AnsiEsc is enabled and one has used set conceallevel=[2 or 3]).

Manual
------

See documentation for detailed description.
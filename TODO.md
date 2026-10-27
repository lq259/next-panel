* Remove GTK 2.0 support
  - GTK 2.0 isn't supplied in any modern OS's anymore.
* Remove all traces of bracketless multiline if statements. Bracketless in a single line is acceptable.
  - This might never be possible to complete 100% complete, but we can at least remove spots with "suspicious indentation".
* Rewrite `panel.c` to C++
* Migrate from Autotools to Mason build system
  - Autotools is quite old and Mason is much more concise.

# Cheaf

The EAF chef – It slices and dices your annotation files any way you like it!
This is a small tool to help you do shell scripting with ELAN’s EAF files.

This is a simple tool I’ve written to extract for the purpose of simplifying
shell scripting with ELAN data. It uses the Python module [pympi-ling] to read
ELAN’s EAF-files, and generates simple line-based output suitable as input in
shell scripts.

Cheaf itself have various subcommands for different tasks, such as listing tier
names, extracting/searching annotations etc.


## Caveat Emptor

This tool was written by me and published here in the hope that it might be
useful to others. It is not to be considered a finished tool, as I'll must
likely return to it every now and then and add or modify stuff to fit my own
needs.

If you find that you need a specific version of this tool for your own shell
scripts to work feel free to included Cheaf with your own software, rather than
installing it as a dependency.


## ELAN

[ELAN] is an annotation tool developed by [The Language Archive] at the [Max
Planck Institute for Psycholinguistics] in the Netherlands. It is used for
annotating video and audio data.

Unfortunately its output data is in XML format, which isn't very shell script
friendly. This tool tries to bridge (some of the gap) between the (horrendous)
XML and the shell.


## Copyright

Written 2019–2022 by zrajm. Released under [Gnu Public License Version
2][GPLv2].

[pympi-ling]: https://pypi.org/project/pympi-ling/
[ELAN]: https://tla.mpi.nl/tools/tla-tools/elan/
[The Language Archive]: https://tla.mpi.nl/tools/tla-tools/
[Max Planck Institute for Psycholinguistics]: https://www.mpi.nl/
[GPLv2]: LICENSE.txt

The Simmons Hall Constitution
=============================

This repository contains the most recent version of MIT's Simmons Hall Student Constitution.

Formats
-------

For convience, many formats of the constitution are provided. Any update to the text of the constitution should be done in `constitution.tex`. All other formats ( e.g. `constitution.pdf`, `constitution.html` ) are compiled versions of the `.tex` file, and should not be directly edited.

Compiling
---------

`compile.sh` contains a bash script for producing all compiled versions. Be warned that this script will create many files. The `.gitignore` should not include these in commits by default.

The ubuntu packages needed to run this script can be found in `DEPENDANCIES.md`.

The Simmons Hall Constitution
=============================

This repository contains the most recent version of MIT's Simmons Hall Student Constitution.

Pull Requests
-------------

This repository represents the official Simmons Hall constitution, and as such should not be edited without the appropriate associated government actions. Commits should not be made directly to the simmons-tech/constitution repository; all changes should be subject to extensive implicit and explicit code review by Simmons Tech and the House.

Some exceptions to this policy may be made for pull requests which only affect the formatting of the constitution. Related files like `compile.sh` are not necessarily subject to code review by the house, but should be properly reviewed by tech.

Formats
-------

For convenience, many formats of the constitution are provided. Any update to the text of the constitution should be done in `constitution.tex`. All other formats ( e.g. `constitution.pdf`, `constitution.html` ) are compiled versions of the `.tex` file, and should not be directly edited.

Compiling
---------

`compile.sh` contains a bash script for producing all compiled versions. Be warned that this script will create many files. The `.gitignore` should not include these in commits by default.

The ubuntu packages needed to run this script can be found in `DEPENDANCIES.md`.

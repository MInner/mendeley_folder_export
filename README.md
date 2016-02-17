# Mendeley Folder PDF Export Tool

This script searches for a Mendeley SQLite db file in your `~`, reads pdf locations and folder structure, and copies those pdfs into folders.

basic usage:

    ./run ~/Dropbox/papers/

to simulate copying without actual copying to see what is going to be copied where use `-s` flag

    ./run -s ~/Dropbox/papers/

**[bug]** for some reason ~5-10% of papers end up being located in wrong directories and 1-2% (with a lot of unicode in the title) are not copied at all.

Dependencies: Python 2.7
Tested on Ubuntu 14.04

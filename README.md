# Mendeley Folder PDF Export Tool

This script searches for a Mendeley SQLite db file in your `~`, reads pdf locations and folder structure, and copies those pdfs into folders.

basic usage:

    ./run ~/Dropbox/papers/

to simulate copying without actual copying to see what is going to be copied where use `-s` flag

    ./run -s ~/Dropbox/papers/

Dependencies: Python 3.4
Tested on Ubuntu 14.04

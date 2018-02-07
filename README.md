
## Issue:
The issue is, that the image transforms fail with *craft 3.0.0-RC9*
when a entry page is first called through the *secondary langauge page*
[craft-3-transform-bug.test/de/](///craft-3-transform-bug.test/de/)
and the *image transform isn't yet indexed!*

## How to Install

Make sure to use 
    DB_TABLE_PREFIX="craft_"
in your *.env* file.

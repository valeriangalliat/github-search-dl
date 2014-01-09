GitHub Search Download
======================

Download matched files from a GitHub code search.

Description
-----------

This software written in Python allows to search for code on GitHub and
to download all the matched files in a tarball.

Dependencies
------------

- `python3`
- `python3-lxml`

Example
-------

This is a kinda funny example, but if you want to get all the Sublime Text
licenses publicly hosted on GitHub in a tarball, you just have to run the
following.

```sh
github-search-dl '"sublime_license" in:path' licenses.tar.gz
```

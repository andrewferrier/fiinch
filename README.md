# What is this?

**⚠️ DEPRECATED: This repository is deprecated, as fiinch was never really finished, and I don't have the time to finish it. For now, it will remain here in case anyone wishes to fork and maintain it.**

This is `fiinch`, the **FI**le **IN**tegrity **CH**ecker. `fiinch`'s ultimate goal is to run a variety of tests against a directory tree. It can be invoked like this:

```
  fiinch <directoryname1> <directoryname2> ...
```

It will recursively check all the files in each directory provided, in turn. If any file doesn't match up to `fiinch`'s checks, it will warn you.

`fiinch` is very much a work in progress. So far, `fiinch` checks for:

* Files where the contents (using the Unix `file` utility) don't seem to match the expected contents, judging by the file extension.

# Installing

A Debian package for `fiinch` can be made with `make builddeb`.

For Debian/Ubuntu, there is support in my sister project [python-deb](https://github.com/andrewferrier/python-deb) for building some dependent modules.

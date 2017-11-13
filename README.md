# jsonnet Format

This package provides jsonnet language formatter. Visual Studio Code will
automatically format the code on save, or you can manually invoke the format
command.

It is set to use the Google [internal
config](https://github.com/google/jsonnet/issues/359), and it's not
configurable, as in long term it might become _the_ default:

```shell
jsonnet fmt --indent 2 --max-blank-lines 2 --sort-imports --string-style s --comment-style s
```

# Install

Make sure `jsonnet` is installed and exists in `$PATH`.
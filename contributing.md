# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test kaf https://github.com/Slijkhuis/asdf-kaf.git "kaf -h"
```

Tests are automatically run in GitHub Actions on push and PR.

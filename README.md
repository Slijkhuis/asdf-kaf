<div align="center">

# asdf-mockgen [![Build](https://github.com/Slijkhuis/asdf-gomock-mockgen/actions/workflows/build.yml/badge.svg)](https://github.com/Slijkhuis/asdf-gomock-mockgen/actions/workflows/build.yml) [![Lint](https://github.com/Slijkhuis/asdf-gomock-mockgen/actions/workflows/lint.yml/badge.svg)](https://github.com/Slijkhuis/asdf-gomock-mockgen/actions/workflows/lint.yml)

[mockgen](https://github.com/golang/mock) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add mockgen https://github.com/Slijkhuis/asdf-gomock-mockgen
```

mockgen:

```shell
# Show all installable versions
asdf list-all mockgen

# Install specific version
asdf install mockgen latest

# Set a version globally (on your ~/.tool-versions file)
asdf global mockgen latest

# Now mockgen commands are available
mockgen --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/Slijkhuis/asdf-gomock-mockgen/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Slijkhuis](https://github.com/Slijkhuis/)
